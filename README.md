# Server

This is a server application built with Express and MongoDB. It provides API endpoints to manage tasks.

## Features

- Allows CRUD operations for tasks
- Supports cross-origin resource sharing (CORS)
- Connects to a MongoDB database

## Prerequisites

Before running the server, make sure you have the following prerequisites installed on your machine:

- Node.js
- MongoDB

## Installation

1. Clone the repository to your local machine.

2. Install the dependencies by running the following command in the project directory:

   ```shell
   npm install

3. Create a .env file in the root directory and provide the required environment variables. Here's an example of the variables you need:


    DB_URI=mongodb://localhost:27017/mydatabase
    FRONTEND_ORIGIN=http://localhost:3000
    PORT=5000
    
    
Adjust the values according to your MongoDB URI, frontend origin, and desired port.

# Usage

To start the server, run the following command in the project directory:

    npm start

The server will start running on the specified port, and you can access the API endpoints at http://localhost:5000/api/tasks.

# API Endpoints

  GET /api/tasks: Get all tasks.
  POST /api/tasks: Create a new task.
  PUT /api/tasks/:id: Update a specific task by ID.
  DELETE /api/tasks/:id: Delete a specific task by ID.


Feel free to explore and test the endpoints using your preferred API testing tool (e.g., Postman).
