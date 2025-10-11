# MERN Portfolio (starter)

This repository contains a starter MERN portfolio with:

- Backend (Express + MongoDB): `/backend`
- Frontend (React + Vite + Tailwind): `/frontend`

## Quick start

1. Backend:
   - cd backend
   - copy `.env.example` to `.env` and set MONGO_URI
   - npm install
   - npm run dev

2. Frontend:
   - cd frontend
   - npm install
   - npm run dev
   - open http://localhost:5173

The frontend contacts the backend POST /api/contact to save messages.

Customize components in `frontend/src/components` and the Mongo model in `backend/models`.
