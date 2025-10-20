
# Kasi Konnect

This is the official repository for Kasi Konnect.

## Project Structure
- `backend/`: Node.js backend with SQLite
- `frontend/`: React frontend
- `render.yaml`: Deployment configuration for Render

## Deployment
Render will automatically detect `render.yaml` and deploy both services.

## Environment Variables
- `PORT`: Backend port (5000)
- `JWT_SECRET`: Secure JWT token
- `NODE_ENV`: production
- `DATABASE_PATH`: /mnt/data/database.db

## Persistent Storage
The backend uses a persistent disk mounted at `/mnt/data`.
