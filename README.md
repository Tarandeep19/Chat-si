# Chat-si: Real-time Chat Application

**Chat-si**, a real-time chat application built with **React** on the frontend and **Node.js** with **Socket.io** on the backend. This project enables seamless real-time messaging between users, providing a great learning experience on how to implement WebSockets using Socket.io.

## Overview
Chat-si is designed to allow users to send and receive messages in real time. By the end of this project, you'll have a solid understanding of how to:

- Set up a basic React frontend.
- Implement real-time communication using Socket.io.
- Develop a Node.js backend to handle WebSocket connections.
- Enable communication between the client and server using WebSockets.

## Features
- **Real-time messaging**: Messages are delivered instantly as soon as they're sent.
- **Socket.io integration**: Efficient two-way communication with the Socket.io library.
- **Responsive UI**: A simple and clean user interface built with React.
- **Multiple users support**: Chat with multiple users in real-time.

## Prerequisites
To run this application, make sure you have the following installed on your machine:
- **Node.js**: [Install Node.js](https://nodejs.org/)
- **npm**: Node Package Manager (comes with Node.js)
- **Git** (optional for cloning the repository)

## Setup Instructions

### 1. Clone the repository
Clone the repository to your local machine by running the following command in your terminal:

```bash
git clone https://github.com/Tarandeep19/Chat-si
```

### 2. Install dependencies
After cloning the repository, navigate to both the **client** and **server** directories and install the necessary dependencies.

- For the **client** (React frontend):
  ```bash
  cd client
  npm install
  ```

- For the **server** (Node.js backend):
  ```bash
  cd server
  npm install
  ```

### 3. Start the development servers
After installing the dependencies, you can start the development servers.

- In the **client** directory, run:
  ```bash
  npm start
  ```
  This will start the React frontend, typically on `http://localhost:3000`.

- In the **server** directory, run:
  ```bash
  npm start
  ```
  This will start the backend server, typically on `http://localhost:5000`.

Now, open `http://localhost:3000` in your browser to start using the chat application. Messages should be instantly received on all connected clients.

## How It Works
1. **Frontend (React)**: React handles the user interface, where users can type messages and send them to other users.
2. **Backend (Node.js + Socket.io)**: The server listens for messages sent from the clients. Using **Socket.io**, it broadcasts the message to all connected clients, ensuring real-time communication.

