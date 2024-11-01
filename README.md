# EduVents: University Event Management System

Welcome to **EduVents**, a full-stack web application designed to streamline event management within a university setting. EduVents allows coordinators to create, manage, and track events, while students can browse, register for, and view events tailored to their interests.

## Technologies Used

- **Frontend**: React, CSS, JavaScript
- **Backend**: Node.js, Express, MongoDB
- **Authentication**: JWT (JSON Web Token)

## Installation Instructions

1. **Download and Extract Files**  
   - Clone or download the repository files and navigate to the project directory.

2. **Backend Setup**  
   - Navigate to the `backend` folder:
     ```bash
     cd backend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Create a `.env` file in the `backend` folder and add the following environment variables:
     ```plaintext
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```
   - Start the backend server:
     ```bash
     npm start
     ```

3. **Frontend Setup**  
   - Open a new terminal, then navigate to the `frontend` folder:
     ```bash
     cd frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the frontend server:
     ```bash
     npm start
     ```
   - Open your browser and navigate to `http://localhost:3000` to access the application.

4. **Set Up Database**  
   - Make sure MongoDB is running. If using MongoDB Atlas, ensure the connection string is updated in the `MONGO_URI` environment variable.

## Features

- **Role-Based Access**: Distinct access for students and coordinators.
- **Event Creation and Management**: Coordinators can create, edit, and delete events.
- **Event Registration**: Students can register for events and view their registered events.
- **Profile Management**: Users can update their profile details and view their activity.
- **Authentication**: Secure JWT-based authentication for all users.

Thank you for exploring EduVents!
