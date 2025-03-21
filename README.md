# Overview  
This is a simple Express.js API for managing movies and user authentication.  

## Features  
- User Registration & Login (with JWT authentication)  
- CRUD operations for movies  

## Installation  

Clone the repository:  

git clone your-repo-url  
cd your-project-folder  

Install dependencies:  

npm install  

Create a .env file and add:  

JWT_SECRET=your-secret-key  
MONGO_URI=your-mongodb-uri  

Start the server:  

npm run dev  

## API Endpoints  

### Authentication  

- POST /api/auth/register – Register a new user  
- POST /api/auth/login – Login and receive a JWT token  

### Movies  

- POST /api/movies – Add a new movie  
- GET /api/movies – Get all movies  
- GET /api/movies/:id – Get a single movie by ID  
- PUT /api/movies/:id – Update movie details  
- DELETE /api/movies/:id – Delete a movie  

## Usage  
Use tools like Postman or cURL to test the API endpoints.  
