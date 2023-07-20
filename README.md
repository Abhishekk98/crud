# crud
This is a MERN (MongoDB, Express.js, React.js, Node.js) stack project that implements a basic user management system.

## Frontend Development

1. Set up a React.js project using Create React App.
2. Created a user interface to interact with the API endpoints.
3. Implemented the following features:
   - Display a list of users retrieved from the backend API.
   - Implemented a form to create a new user and send the data to the backend API.
   - Allow updating and deleting users from the frontend interface.
4. Client-side input validation and error handling are implemented.

## Development Environment Setup

1. Install Node.js and MongoDB on your machine.
2. Create a new project folder and initialize a new Node.js project using `npm init`.
3. Install necessary packages and dependencies for both the backend and frontend using `npm install` in the root and `frontend` folder, respectively.

## Backend Development

1. Create a MongoDB database and set up a connection using Mongoose.
2. Design and implement a RESTful API using Express.js to perform CRUD operations on a "users" collection in the MongoDB database.
3. The API has the following endpoints:
   - GET /users: Get all users
   - POST /users: Create a new user
4. Input validation and error handling are implemented for the API endpoints.



## Additional Tasks (Optional)

We implemented user authentication using JSON Web Tokens (JWT) for securing the API endpoints.

## How to Run the Project

1. Start the backend server:
   - Navigate to the root of the project folder.
   - Run `node index.js` to start the backend server.

2. Start the frontend development server:
   - Navigate to the `frontend` folder.
   - Run `npm start` to start the frontend development server.

3. Access the application:
   - Open your browser and go to `http://localhost:3000/` to access the frontend.

## Evaluation Criteria

This project demonstrates the use of the MERN stack and includes features such as a RESTful API, proper input validation, error handling, and React.js components for interacting with the API endpoints.

[Optional Task Completion - Add any details related to the optional tasks you completed]

