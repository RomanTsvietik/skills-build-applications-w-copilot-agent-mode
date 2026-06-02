# 🐙 OctoFit Tracker

A modern multi-tier fitness tracking application built with GitHub Copilot agent mode.

## Architecture

### Presentation Tier (Frontend)
- **Technology**: React 19
- **Build Tool**: Vite
- **Port**: 5173 (public)
- **Location**: `octofit-tracker/frontend`

### Logic Tier (Backend)
- **Technology**: Node.js + Express + TypeScript
- **Port**: 8000 (public)
- **Location**: `octofit-tracker/backend`

### Data Tier
- **Technology**: MongoDB
- **Port**: 27017 (private)
- **Database**: octofit-tracker

## Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB (running on localhost:27017)

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Access the frontend at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

Access the backend at `http://localhost:8000`

## API Endpoints

- `GET /` - Root endpoint
- `GET /api/health` - Health check endpoint

## Development

- Frontend: `npm run dev` (with hot reload)
- Backend: `npm run dev` (with tsx loader)
- Build: `npm run build`

## License

ISC
