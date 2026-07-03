# Todo App - ASP.NET Core + React

A full-stack todo application built with ASP.NET Core backend API and React frontend.

## Project Structure

```
├── backend/                 # ASP.NET Core API
│   ├── TodoApp.Api/        # Main API project
│   ├── TodoApp.Models/     # Shared data models
│   └── TodoApp.sln         # Solution file
│
├── frontend/               # React application
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── pages/         # Page components
│   │   ├── services/      # API services
│   │   ├── App.tsx        # Main App component
│   │   └── main.tsx       # Entry point
│   └── package.json       # Dependencies
│
└── README.md
```

## Prerequisites

- .NET 8.0 SDK or later
- Node.js 18.0 or later
- npm or yarn

## Getting Started

### Backend Setup

```bash
cd backend
dotnet restore
dotnet run --project TodoApp.Api
```

The API will run on `https://localhost:5001`

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The React app will run on `http://localhost:5173`

## Features

- Create, read, update, and delete todos
- Mark todos as complete/incomplete
- Filter todos by status
- Persistent data with database

## Technologies

**Backend:**
- ASP.NET Core 8.0
- Entity Framework Core
- SQL Server/SQLite

**Frontend:**
- React 18+
- TypeScript
- Vite
- Axios for API calls
- Tailwind CSS
