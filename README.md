MERN Stack Real-Time Chat Application
A full-stack real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js), Socket.io for real-time communication, and JWT for secure user authentication.

Project Overview
This project demonstrates how to create a scalable and responsive chat application where users can sign up, log in, send messages in real time, and manage user profiles. It incorporates best practices for authentication, state management, and backend API development.

Features
User signup and login with JWT authentication

Password hashing for security using bcryptjs

Profile photo upload and management

Real-time messaging using Socket.io

Fetch and display conversation messages with other users

Search users functionality

Persistent user sessions with Redux state management

Responsive UI styled with Tailwind CSS and Daisy UI

Technologies Used
Frontend: React, Redux, Tailwind CSS, Daisy UI

Backend: Node.js, Express.js, MongoDB, Mongoose

Real-time communication: Socket.io

Authentication: JWT, bcryptjs

State Management: Redux toolkit

Installation and Setup
Prerequisites
Node.js and npm installed

MongoDB account or local installation

Setup Steps
Clone the repository:

bash
git clone https://github.com/Surendrakumarpatel/yt-chat-application.git
Navigate to the backend directory and install dependencies:

bash
cd backend
npm install
Configure environment variables in a .env file (e.g., MongoDB URI, JWT secret).

Start the backend server:

bash
npm run dev
Navigate to the frontend directory and install dependencies:

bash
cd ../frontend
npm install
Start the frontend development server:

bash
npm start
The application will be accessible at http://localhost:3000.

Usage
Register as a new user or log in.

Upload a profile photo.

Search for users and start chatting in real time.

Messages update live using Socket.io.

Manage your account and sessions.
