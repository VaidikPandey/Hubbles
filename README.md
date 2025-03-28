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

## API Documentation

- `POST /api/auth/register` - User registration
- `POST /api/auth/login` - User authentication
- `GET /api/messages` - Fetch message history
- `POST /api/messages` - Send new message

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/awesome-feature`)
3. Commit changes (`git commit -m 'Add awesome feature'`)
4. Push to branch (`git push origin feature/awesome-feature`)
5. Open a Pull Request

## License

MIT License
