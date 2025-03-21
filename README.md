# Collab-Code

## Overview

Collab-Code is a real-time collaborative code editor and development environment that allows multiple developers to work together on coding projects simultaneously. It features:

- Real-time code collaboration
- Built-in code execution environment
- AI-powered code assistance
- Project management capabilities
- Secure user authentication
- File tree management
- Live chat between collaborators

## Prerequisites

- Node.js (v16 or higher)
- npm (v8 or higher) or yarn (v1.22 or higher)
- Git
- MongoDB (v5 or higher)
- Redis (v6 or higher)

## Getting Started

### Installation

1. Clone the repository

```bash
git clone https://github.com/anushka1822/Collab-Code.git
cd Collab-Code
```

2. Install dependencies for both frontend and backend

```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables

```bash
# Backend .env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
REDIS_HOST=your_redis_host
REDIS_PORT=your_redis_port
REDIS_PASSWORD=your_redis_password
GOOGLE_AI_KEY=your_google_ai_key

# Frontend .env
VITE_API_URL=http://localhost:3000
```

### Development

To start the development servers:

```bash
# Start backend server
cd backend
npm run dev

# Start frontend server in a new terminal
cd frontend
npm run dev
```

### Building

To build for production:

```bash
# Build frontend
cd frontend
npm run build

# Build backend
cd backend
npm run build
```

## Project Structure

```
Collab-Code/
├── backend/           # Backend server code
│   ├── controllers/   # Request handlers
│   ├── models/       # Database models
│   ├── routes/       # API routes
│   ├── services/     # Business logic
│   └── middleware/   # Custom middleware
├── frontend/         # Frontend React application
│   ├── src/         # Source code
│   ├── public/      # Static assets
│   └── config/      # Configuration files
└── docs/            # Documentation
