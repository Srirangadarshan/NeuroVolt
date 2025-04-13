# NeuroVolt 
# Stock Market Data Visualization

A modern web application for visualizing and analyzing stock market data in real-time. This project consists of a React-based frontend dashboard and a Node.js backend server that processes and serves stock market data.

## Features

- Real-time stock data visualization
- Interactive charts and graphs
- Multiple stock comparison capabilities
- Historical data analysis
- Responsive dashboard design

## Tech Stack

- **Frontend**: React.js with Plotly.js for data visualization
- **Backend**: Node.js with Express
- **Database**: PostgreSQL
- **Development Tools**: 
  - Concurrent development server
  - Nodemon for automatic server restart
  - CORS enabled for secure cross-origin requests

## Project Structure

```
NeuroVolt/
├── Dashboard/          # React frontend application
├── StockData/          # CSV data files for stocks
├── server.js           # Express backend server
└── package.json        # Project dependencies and scripts
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)
- PostgreSQL

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/NeuroVolt.git
cd NeuroVolt
```

2. Install dependencies:
```bash
npm install --legacy-peer-deps && cd Dashboard && npm install --legacy-peer-deps
```

3. Start the development server:
```bash
npm run dev
```

This will start both the frontend (on port 3000) and backend (on port 3001) servers concurrently.

## API Endpoints

- `GET /api/stocks` - Get list of available stocks
- `GET /api/stocks/:symbol` - Get detailed data for a specific stock

## Development

The project uses a concurrent development setup where both the frontend and backend servers run simultaneously. The frontend is built with React and uses Plotly.js for data visualization, while the backend serves stock data from CSV files and provides a RESTful API.


## Acknowledgments

- Plotly.js for interactive data visualization
- Express.js for the robust backend framework
- React.js for the modern frontend framework
