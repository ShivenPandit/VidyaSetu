# VidyaSetu - Quick Start Guide

### Step 1: Install Dependencies

**Backend:**
```powershell
cd backend
npm install
```

**Frontend:**
```powershell
cd frontend
npm install
```

### Step 2: Configure Environment Variables

**Backend** (`backend/.env`):
```env
PORT=5000
NODE_ENV=development
MONGODB_URI=mongodb+srv://your-connection-string
JWT_SECRET=your-secret-key-minimum-32-characters
JWT_EXPIRE=7d
FRONTEND_URL=http://localhost:3000
MAX_FILE_SIZE=50000000
```

**Frontend** (`frontend/.env`):
```env
VITE_API_URL=http://localhost:5000/api
VITE_APP_NAME=VidyaSetu
```
