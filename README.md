# Video Conferencing Platform

A full-stack video conferencing web application built using the MERN stack and Socket.IO. This platform allows users to create and join video meetings in real time.

## Features

* User Authentication
* Create and Join Video Meetings
* Real-time Video & Audio Communication
* Meeting Room Management
* Socket.IO based Real-time Communication
* Responsive User Interface

## Tech Stack

### Frontend

* React.js
* CSS
* Axios

### Backend

* Node.js
* Express.js
* Socket.IO
* MongoDB
* Mongoose

## Project Structure

```bash
Video-Conferencing-Platform/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── package.json
│   └── app.js
│
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/Surajitp/Video-Conferencing-Platform.git
cd Video-Conferencing-Platform
```

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
MONGO_URL=your_mongodb_connection_string
PORT=8000
```

Start Backend Server:

```bash
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## Usage

1. Register/Login to the application.
2. Create a new meeting room.
3. Share the room link with participants.
4. Join the room and start video conferencing.

## Future Enhancements

* Screen Sharing
* Meeting Recording
* Chat Functionality
* Participant Controls
* File Sharing

## Author

**Suraj Kumar**

GitHub: https://github.com/Surajitp

