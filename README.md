# Hubbles - Real-Time Chat Application

A modern full-stack real-time chat application built with MERN Stack and Socket.IO, delivering seamless instant messaging experience.

## Features

- User authentication with JWT
- Real-time messaging
- User presence detection
- Message history with MongoDB
- Responsive modern UI
- State management with Zustand

## Tech Stack

- MongoDB
- Express.js
- React.js
- Node.js
- Socket.IO
- TailwindCSS
- Daisy UI
- Zustand
- JWT

## Installation

1. Clone the repository

```bash
git clone https://github.com/VaidikPandey/hubbles.git
```

2. Install dependencies for both backend and frontend

```bash
cd hubbles
npm install
cd client
npm install
```

3. Configure environment variables

Create `.env` in root directory:

```
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

4. Start the application

```bash
# Start backend
npm run server

# Start frontend
cd client
npm start
```

5. Open `http://localhost:3000` in your browser
