# FinMarkets Hub

A real-time financial news app focused on the Indian market and global economy. Aggregates news from multiple sources and integrates market data using the Finnhub API.

## Features
- Real-time financial news aggregation
- Multi-source news from ET, Financial Express, Bloomberg, FT
- Finnhub market data
- User authentication
- Ad integration for revenue

## Tech Stack
- Frontend: React.js
- Backend: Node.js + Express
- Database: MongoDB (via Mongoose)
- News Aggregation: RSS / APIs
- Hosting: Vercel (Frontend), Render (Backend)

## Getting Started
```bash
# Clone the repo
git clone https://github.com/yourusername/finmarkets-hub.git
cd finmarkets-hub

# Setup backend
cd backend
npm install

# Setup frontend
cd ../frontend
npm install
```

## Environment Variables
Create `.env` files in both `frontend` and `backend`:

### backend/.env
```
PORT=5000
MONGO_URI=your_mongo_uri
FINNHUB_API_KEY=your_finnhub_key
```

### frontend/.env
```
REACT_APP_API_URL=http://localhost:5000
```

## Run Dev Servers
```bash
# Backend
cd backend
npm run dev

# Frontend
cd ../frontend
npm start
```
