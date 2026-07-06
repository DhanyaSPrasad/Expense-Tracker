# Expense Tracker

A full-stack expense tracker built with React, Vite, Express, and MongoDB. It supports user authentication, expense tracking, category summaries, and a responsive UI.

## Features

- User registration and login with JWT authentication
- Add, edit, and delete expenses
- Track amount, category, description, and date
- View spending summaries by category
- Responsive interface for desktop and mobile
- Dark mode styling and grid/list-friendly layout
- Persistent data stored in MongoDB

## Tech Stack

- Frontend: React, Vite, Axios, CSS
- Backend: Node.js, Express, MongoDB, JWT, bcryptjs, CORS

## Project Structure

- `src/` - React frontend source
- `public/` - Static assets
- `server.js` - Express API and MongoDB connection

## Getting Started

### Prerequisites

- Node.js
- MongoDB running locally on `mongodb://localhost:27017`

### Install Dependencies

```bash
npm install
```

### Run the App

Frontend and backend together:

```bash
npm run dev
```

Backend only:

```bash
npm run server
```

Frontend only:

```bash
npm run client
```

## Scripts

- `npm run dev` - Start frontend and backend together
- `npm run server` - Start the Express API
- `npm run client` - Start the Vite frontend
- `npm run build` - Build the frontend for production
- `npm run preview` - Preview the production build
- `npm start` - Start the backend server

## API Overview

### Auth

- `POST /api/auth/register`
- `POST /api/auth/login`

### Expenses

- `GET /api/expenses`
- `POST /api/expenses`
- `PUT /api/expenses/:id`
- `DELETE /api/expenses/:id`
- `GET /api/expenses/summary`

### User

- `GET /api/user`
- `PUT /api/user`

## Notes

- The app expects MongoDB to be installed and running locally.
- The background image used by the frontend is stored at the repository root as `bck-wt.JPG`.
