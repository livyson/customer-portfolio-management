# Customer Portfolio Management System

A modern web application for managing customer portfolios, built with React, Node.js, Express, and PostgreSQL.

## Features

- Customer portfolio creation and management
- Real-time portfolio tracking
- Secure authentication and authorization
- Responsive design for all devices
- Data visualization and analytics
- RESTful API architecture

## Tech Stack

- **Frontend:**
  - React.js
  - TypeScript
  - Material-UI
  - Redux Toolkit
  - React Query
  - Chart.js for data visualization

- **Backend:**
  - Node.js
  - Express.js
  - TypeScript
  - PostgreSQL
  - Prisma ORM
  - JWT Authentication

## Prerequisites

- Node.js (v18 or higher)
- PostgreSQL (v14 or higher)
- npm or yarn package manager

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-portfolio-management.git
   cd customer-portfolio-management
   ```

2. Install dependencies:
   ```bash
   # Install backend dependencies
   cd backend
   npm install

   # Install frontend dependencies
   cd ../frontend
   npm install
   ```

3. Set up environment variables:
   - Copy `.env.example` to `.env` in both frontend and backend directories
   - Update the variables with your configuration

4. Set up the database:
   ```bash
   cd backend
   npx prisma migrate dev
   ```

5. Start the development servers:
   ```bash
   # Start backend server (from backend directory)
   npm run dev

   # Start frontend server (from frontend directory)
   npm run dev
   ```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:8000

## Project Structure

```
customer-portfolio-management/
├── frontend/               # React frontend application
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/        # Page components
│   │   ├── services/     # API services
│   │   ├── store/        # Redux store
│   │   └── utils/        # Utility functions
│   └── public/           # Static files
│
├── backend/               # Node.js backend application
│   ├── src/
│   │   ├── controllers/  # Route controllers
│   │   ├── models/       # Database models
│   │   ├── routes/       # API routes
│   │   ├── services/     # Business logic
│   │   └── utils/        # Utility functions
│   └── prisma/          # Database schema and migrations
│
└── docs/                 # Documentation
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, please open an issue in the GitHub repository or contact the maintainers.