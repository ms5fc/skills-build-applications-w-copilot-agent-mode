# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js/Express, and MongoDB.

## Architecture

### Frontend
- **Framework**: React 19 with TypeScript
- **Build Tool**: Vite
- **Port**: 5173
- **Features**: Component-based UI, real-time updates

### Backend
- **Runtime**: Node.js with TypeScript
- **Framework**: Express.js
- **Port**: 8000
- **Database**: MongoDB (localhost:27017)
- **ORM**: Mongoose

### Database
- **MongoDB**: Port 27017
- **Database Name**: octofit

## Getting Started

### Prerequisites
- Node.js 18+
- npm or yarn
- MongoDB running locally or connection string configured

### Setup Instructions

#### Frontend
```bash
cd octofit-tracker/frontend
npm install
npm run dev
```
Frontend will be available at: http://localhost:5173

#### Backend
```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```
Backend API will be available at: http://localhost:8000

#### MongoDB
Ensure MongoDB is running on localhost:27017

## API Endpoints

- `GET /health` - Health check
- `GET /api/status` - API status with MongoDB connection state

## Development

Both frontend and backend support hot module reloading during development.