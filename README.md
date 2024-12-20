# LOKALAN

A full-stack web application for connecting local food producers with consumers.

## Prerequisites

- Python 3.12+
- Node.js 18+
- MySQL 8.0+

## Quick Start

1. Clone the repository
2. Copy and configure environment files:
```bash
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env.local
```
3. Install dependencies:
```bash
# Backend
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Frontend
cd ../frontend
npm install
```

4. Initialize database:
```bash
cd backend
python init_db.py
```

5. Start development servers:
```bash
# Make script executable
chmod +x dev.sh
# Run both servers
./dev.sh
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend API: http://localhost:5000
- API Documentation: http://localhost:5000/docs