MERN Stack Real-Time Chat Application

A full-stack real-time chat application built with the MERN stack (MongoDB, Express, React, Node.js), Socket.io for real-time messaging, and JWT for secure authentication. Users can sign up, log in, manage profiles, and chat with others in real-time using a responsive and scalable interface.




Features

User signup and login with JWT authentication
Secure password hashing with bcryptjs
Profile photo upload and management
Real-time bi-directional messaging using Socket.io
Dynamic fetching and display of conversation messages
User search functionality to find and chat with others
Persistent user sessions managed through Redux
Responsive UI styled with Tailwind CSS and DaisyUI



Technologies Used
Frontend: React, Redux Toolkit, Tailwind CSS, DaisyUI
Backend: Node.js, Express, MongoDB, Mongoose
Real-time Communication: Socket.io
Authentication/Security: JWT, bcryptjs



Installation and Setup
Prerequisites

Node.js and npm installed

MongoDB instance (local or cloud)



Backend Setup
cd yt-chat-application/backend
npm install


Configure environment variables in .env file (MongoDB URI, JWT secret, etc.)

npm run dev

3. Frontend Setup
cd ../frontend
npm install
npm start


Open your browser at http://localhost:3000

Usage

Register or log in with your credentials

Upload and manage your profile photo

Search users and open chat conversations

Send and receive messages instantly in real-time

Manage sessions and log out securely
