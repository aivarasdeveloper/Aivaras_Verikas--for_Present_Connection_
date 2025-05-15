# Group Expense Tracker

This is a full-stack project I created to practice working with user groups and shared expense management.

## Technologies

Backend:
- ASP.NET Core
- Entity Framework Core (using in-memory database)
- Swagger for testing endpoints
- xUnit for unit testing

Frontend:
- React (with TypeScript)
- Material UI
- Axios
- Vite for dev server and build

DevOps:
- Docker & docker-compose
- GitHub Actions CI

## Features

- Create groups and add users
- Track transactions between members
- Split expenses equally or with custom amounts
- Swagger UI to test API
- Fully responsive frontend with Material UI
- Docker support for local setup
- CI pipeline with GitHub Actions
- Includes some demo seed data

## How to Run

### Backend
```
cd backend/GroupExpenseTracker.API
dotnet restore
dotnet run
```

### Frontend
```
cd frontend
npm install
npm run dev
```

## Docker

You can run the whole project with Docker:
```
docker-compose up --build
```

- Frontend: http://localhost:5173
- Backend/Swagger: http://localhost:5000/swagger

## Notes

I used Swagger to check the endpoints while testing the backend.
Frontend was bootstrapped with Vite and uses react-router.
The database is in-memory only, just for demonstration.
