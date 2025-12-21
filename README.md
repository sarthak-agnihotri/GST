GST Software
This project consists of a Node.js/Express backend and a React frontend.

Prerequisites
Node.js installed
MongoDB installed and running
Setup and Running
Backend
Navigate to the backend directory:

cd backend
Install dependencies:

npm install
Set up environment variables:

Ensure .env file exists in backend/ with the following content:
NODE_ENV=development
PORT=5000
MONGO_URI=mongodb://localhost:27017/gst_software
JWT_SECRET=your_jwt_secret_key_here
Start the server:

npm start
The server will run on http://localhost:5000.

Frontend
Navigate to the frontend directory:

cd frontend
Install dependencies:

npm install
Start the application:

npm start
The application will open in your browser at http://localhost:3000.

Project Structure
backend/: Contains the Express server, API routes, controllers, and database models.
frontend/: Contains the React application.
