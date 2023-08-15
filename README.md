# Books&Quotes

A simple CRUD app build with Angular and ASP.NET Web API with JWT Authentication.

## Technologies used

### Frontend

- Angular
- Typescript
- Bootstrap

### Backend

- .NET 6
- Entity Framework Core
- JSON Web Token

## Installation and Usage

To run this app start with backend API server first.

### Backend Server

First edit Token in `backend/appsettings.json` to JWT secret key.

```bash
 "AppSettings" : {
    "Token" : "YOUR_SECRET_TOKEN"
}
```

To run the server navigate to the backend folder.

```bash
cd backend
```

To start the server run this command.

```bash
dotnet run
```

The server will run at `http://localhost:5000`.

### Fronend Client

First navigate to the frontend folder.

```bash
cd frontend
```

Install the packages.

```bash
npm install
```

or

```bash
yarn install
```

To run the app use

```bash
ng serve
```

The client will run at `http://localhost:4200`.
