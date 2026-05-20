# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Vite, Node.js, Express, TypeScript, and MongoDB.

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
├── backend/           # Node.js + Express + TypeScript API
└── README.md         # This file
```

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- MongoDB (running on port 27017)

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Frontend will be available at: `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

Backend API will be available at: `http://localhost:8000`

### MongoDB Setup

Ensure MongoDB is running on port 27017:

```bash
mongod --port 27017
```

## Configuration

### Ports

- **Frontend**: 5173 (Vite dev server)
- **Backend**: 8000 (Express server)
- **MongoDB**: 27017

### Environment Variables

Copy `.env.example` to `.env` in the root directory:

```bash
cp .env.example .env
```

## API Endpoints

- `GET /` - API info
- `GET /health` - Health check

## Development

### Frontend Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

### Backend Commands

- `npm run dev` - Start development server with ts-node
- `npm run build` - Compile TypeScript to JavaScript
- `npm run start` - Run compiled JavaScript

## Technologies

- **Frontend**: React 19, Vite, JavaScript/JSX
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB, Mongoose ODM
- **Development**: ts-node, TypeScript compiler

## License

MIT
