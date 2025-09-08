# Project Overview
This project was created to practice the use of **JWT**, especially in authentication.  
It is similar to the previous project, which also made use of an API. The API  
supports user registration, login, and other operations while ensuring that  
information is protected.

All endpoints were tested using Postman.

### Setup
- Clone the repo
- Install dependencies (npm install)
- Create .env file in the project root (check .env.example for reference)
- Run using terminal (npm run dev)

## Endpoints
- GET /api/health - Health check
- POST /api/auth/signup - Register new user
- POST /api/auth/login - Login user
- POST /api/auth/logout - Logout user
- GET /api/profile - Get user profile
