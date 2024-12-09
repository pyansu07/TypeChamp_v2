# TypeChamp

TypeChamp is a real-time multiplayer typing game developed using React, JavaScript, WebSockets, and CSS. It offers an engaging and interactive experience by allowing players to compete in typing challenges in real time.

## Features

- `Real-time Multiplayer`: Play against other users in real-time typing competitions.
- `WebSocket` Communication: Utilizes `Socket.IO` for seamless real-time communication between players.
- `Chat` feature to communicate with matched users
- `Live` leaderboard update.
- `Automatic` room assignment

## Technologies Used

- ReactJS: For building the user interface.
- JavaScript: For game logic and client-side functionality.
- Socket.IO: For real-time communication.
- CSS: For styling the application and ensuring responsive design.

## WebSocket Implementation

The WebSocket communication is implemented using Socket.IO to ensure real-time interaction between players. This allows for smooth and responsive multiplayer gameplay.

### 🌐Server-Side (Socket.IO)
The server manages real-time game communications using Socket.IO with the following key features:
#### 1. Room Management
#### 2. Game State Management

### 💻Client-Side Implementation
#### 1.Socket Connection
#### 2.Game States

### 🤖Other Technical Implementation

1.**Error Handling**
   - Disconnection management
   - Room cleanup
   - Player state preservation


### 📌Development Setup

1. **Server Requirements**
   - Node.js
   - Socket.IO server package
   - HTTP server setup

2. **Client Requirements**
   - React
   - Socket.IO client package
   - SweetAlert2 for notifications
## Installation

## Step-1: Clone the repository:

```bash
git clone "<--->"
```
## step-2: Install dependencies:

```bash
cd client
npm install
```

```bash
cd server
npm install
```

## Step-3: Start the development server:

```bash
cd server
node server.js
```
## Step-4: Start the app:
```bash
cd client
npm run dev
```



