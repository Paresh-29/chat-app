# Chat Application

This is a real-time chat application built using Node.js, Express, and Socket.IO for the backend, and React with Zustand for state management on the frontend. The design is styled using Tailwind CSS and DaisyUI.

## Features
- Real-time messaging with Socket.IO
- User authentication and authorization
- Profile management
- Theme support with various themes
- Responsive design

## Installation

### Prerequisites
- Node.js
- npm (Node Package Manager)
- MongoDB

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Paresh-29/chat-app.git
   cd chat-app
   ```

2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```

4. Create a `.env` file in the `backend` directory and add the following environment variables:
   ```env
   PORT=your_port
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   NODE_ENV=development
   ```

5. Start the backend server:
   ```bash
   cd backend
   npm run dev
   ```

6. Start the frontend server:
   ```bash
   cd ../frontend
   npm run dev
   ```

## Usage
1. Open your browser and navigate to [chat-app-h3qd.onrender.com](https://chat-app-h3qd.onrender.com).
2. Register a new account or log in with existing credentials.
3. Start chatting with other users in real-time.

## Project Structure
- **backend/**: Contains the backend server code using Express.js.
  - **controllers/**: Contains the controllers for handling requests.
  - **lib/**: Contains the database connection and Socket.IO setup.
  - **middleware/**: Contains the middleware for authentication.
  - **models/**: Contains the schemas for MongoDB.
  - **routes/**: Contains the route definitions for authentication and messaging.
  - **seeds/**: Contains the seed data for the database.
  - **index.js**: Main entry point for the backend server.
- **frontend/**: Contains the frontend code developed using React.
  - **components/**: Contains the React components.
  - **constants/**: Contains theme constants and other constants.
  - **lib/**: Contains utility functions and libraries.
  - **pages/**: Contains the main page components.
  - **store/**: Contains Zustand store setup.
  - **App.jsx**: Main application component.
  - **index.css**: Main CSS file for styling using Tailwind CSS and DaisyUI.
  - **main.jsx**: Entry point for the React application.

## Contributing
Feel free to fork this repository and contribute by submitting a pull request. Any contributions, issues, and feature requests are welcome.
