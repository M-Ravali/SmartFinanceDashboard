# Finance Dashboard

A comprehensive personal finance analytics dashboard built with the MERN stack (MongoDB, Express, React, Node.js).


## Overview

This Finance Dashboard application provides a complete visualization of personal or business financial data. It offers insightful analytics, predictive trends, and comprehensive reporting to help users make informed financial decisions.

## Features

- **Interactive Dashboard**: Real-time overview of financial status
- **Expense Tracking**: Categorize and track all expenses
- **Income Management**: Monitor all income sources
- **Budget Planning**: Create and manage budgets
- **Investment Tracking**: Monitor investment performance
- **Predictive Analytics**: ML-powered financial forecasting
- **Data Visualization**: Charts and graphs for easy understanding
- **Responsive Design**: Works on desktop and mobile devices
- **Secure Authentication**: Protects your financial data

## Tech Stack

- **Frontend**: React, Redux, Material-UI, Recharts
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Deployment**: Docker, AWS/Heroku

## Getting Started

### Prerequisites

- Node.js (v14+)
- MongoDB
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/M-Ravali/SmartFinanceDashboard.git
cd SmartFinanceDashboard
```

2. Install dependencies for both server and client
```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

3. Set up environment variables
```bash
# In the server directory, create a .env file
touch .env

# Add the following variables to the .env file
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

4. Start the development servers
```bash
# Start the backend server
cd server
npm run dev

# In a new terminal, start the frontend server
cd client
npm run dev
```

5. Open your browser and navigate to `http://localhost:3000`

### Configuration

- Database configuration can be modified in `server/config/db.js`
- API endpoints are defined in `server/routes/`
- Frontend components are located in `client/src/components/`

## Usage

1. Use the dashboard to visualize your financial status
2. Set up budgets and financial goals
3. Generate reports for insights into your spending habits

## API Documentation

The API documentation can be found at `/api/docs` when the server is running.

## Deployment

### Docker

```bash
# Build the Docker image
docker-compose build

# Run the container
docker-compose up
```

### Manual Deployment

- Frontend can be deployed to Netlify, Vercel, or similar services
- Backend can be deployed to Heroku, AWS, or other cloud providers

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- Based on the MERN Finance Dashboard tutorial by [Tutorial Creator]
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express Documentation](https://expressjs.com/)
- [Node.js Documentation](https://nodejs.org/en/docs/)

## Contact

Ravali Maddela - ravalimaddela14@gmail.com

Project Link: [https://github.com/M-Ravali/SmartFinanceDashboard.git](https://github.com/M-Ravali/SmartFinanceDashboard.git)