# NeuroVolt 
# Stock Market Data Visualization

A modern web application for visualizing and analyzing stock market data in real-time. This project consists of a React-based frontend dashboard and a Node.js backend server that processes and serves stock market data.

# Video Link

https://drive.google.com/file/d/11Ww0QZ3UMi3I9ihjhZpJQoio7FR6vfm6/view?usp=sharing

### Screenshot

<img width="1391" alt="Screenshot 2025-04-13 at 19 49 20" src="https://github.com/user-attachments/assets/04426bab-2e17-41c9-a7b2-f265b0d31ac9" />

## Features

- local stock data and real time stock tracking 
- search and filtering datasets efficiently
- add/remove stocks to personal watchlist
- advanced data visualizations 
- technical analysis ex: RSI, SMA20, volatility measures and store any visuals easily
- exporting watchlist to csv
- AI- powered market insights 
- AI assistance chat bot for stock market using gemini 
- settings for customizing and controlling

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

# Getting Started

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
