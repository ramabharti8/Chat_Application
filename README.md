## Real-Time Chat Application
# Chat_Application 

## Overview

This Real-Time Chat Application is a full-stack web application developed using ReactJS, Express, NodeJS, and MongoDB. The application allows users to create an account, log in, and engage in real-time conversations with other users. It features user authentication, profile management, and real-time messaging functionality.

## Project Setup

### MongoDB Setup

1. **Install MongoDB**: Ensure MongoDB is installed on your machine or use a cloud-based MongoDB service like MongoDB Atlas.
2. **Create a Database**: Set up a new database for the chat application.
3. **Create Models**: Define the data models for users and messages.

### Backend Setup

1. **Signup Endpoint**: Implement the endpoint to handle user registration.
2. **Bcryptjs**: Use Bcryptjs to hash user passwords for secure storage.
3. **User Profile Photo API**: Create an API for users to upload and manage their profile photos.
4. **User Route Setup**: Define routes for user-related operations.
5. **Login Endpoint**: Implement the endpoint for user login.
6. **Generate JWT Token**: Generate JWT tokens for authentication.
7. **Authentication Middleware**: Create middleware to protect routes and ensure user authentication.
8. **Get Other User Endpoint**: Implement an endpoint to retrieve information about other users.
9. **Send Message Endpoint**: Create an endpoint to send messages.
10. **Get Message Endpoint**: Implement an endpoint to retrieve messages.

### Frontend Setup

1. **React Setup**: Initialize the React project.
2. **Tailwind + Daisy UI Setup**: Integrate Tailwind CSS and DaisyUI for styling.
3. **Create Frontend Routing**: Set up routing using React Router.
4. **Create Signup + Login Page**: Design and implement the user registration and login pages.
5. **Signup + Login API Call**: Connect the frontend with backend APIs for user signup and login.
6. **Redux Setup**: Set up Redux for state management.
7. **Home Page Design**: Design the home page where users can interact and view messages.
8. **Get Other Users Custom Hook**: Create a custom hook to fetch and manage other users.
9. **Logout API Call**: Implement the API call for user logout.
10. **Get Messages**: Fetch and display messages on the frontend.
11. **Send Message**: Implement functionality to send messages.
12. **Search Users**: Add a feature to search for other users.

### Implementing Socket.io

1. **Real-Time Communication**: Integrate Socket.io to enable real-time messaging between users.
2. **Persist Our Store**: Ensure that the application's state is preserved across sessions.

## Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ramabharti8/Chat_Application.git
   ```
2. **Install Dependencies**:
   ```bash
   cd Chat_Application 
   ```
3. **Set Up Environment Variables**: Create a `.env` file in the root directory and configure the necessary environment variables for MongoDB, JWT secret, etc.
4. **Run the Application**:
   ```bash
   cd backend --> npm install --> npm run dev
   cd frontend --> npm install --> npm start
   ```
5. **Visit the Application**: Open your browser and navigate to `http://localhost:3000`.

## Future Updates

Stay tuned for more exciting updates as we continue to enhance and add new features to the application.
