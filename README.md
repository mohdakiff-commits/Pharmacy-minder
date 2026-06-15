# Pharmacy Minder

A comprehensive pharmacy management system built with React (Vite) and Node.js (Express).

## Features

- **User Authentication** - Secure login with JWT
- **Inventory Management** - Track medicines, stock levels, expiry dates
- **Sales Tracking** - Record and manage sales transactions
- **Customer Management** - Maintain customer profiles and purchase history
- **Dashboard** - Real-time analytics and business metrics

## Tech Stack

**Frontend:**
- React 18 + Vite
- Axios for API calls
- React Router for navigation
- Context API for state management

**Backend:**
- Node.js + Express
- PostgreSQL / MongoDB
- JWT Authentication
- Zod for validation

## Getting Started

### Prerequisites
- Node.js (v16+)
- PostgreSQL or MongoDB
- npm or yarn

### Installation

1. **Install dependencies**

Frontend:
```bash
cd client
npm install
```

Backend:
```bash
cd server
npm install
```

2. **Environment Setup**

Create `.env` files in both `client/` and `server/` directories.

**server/.env:**
```
PORT=5000
DATABASE_URL=postgresql://user:password@localhost:5432/pharmacy_db
JWT_SECRET=your_jwt_secret_key
NODE_ENV=development
```

**client/.env:**
```
VITE_API_URL=http://localhost:5000/api
```

3. **Run the application**

Backend:
```bash
cd server
npm run dev
```

Frontend:
```bash
cd client
npm run dev
```

## API Documentation

See `docs/api-docs.md` for detailed API endpoints.

## License

MIT