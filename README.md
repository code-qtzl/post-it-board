# Post-it-Board App

<div align="left">
  <img src="./client/public/post-it-note.svg" alt="post-it-note svg" width="80"/>
</div>
A post-it-board application for posting and viewing messages built with React frontend (Vite) and Node.js backend, both using TypeScript.

## Prerequisites

-   Node.js (v16 or higher)
-   npm or yarn

## Setup

1. Install dependencies for both client and server:

```bash
git clone https://github.com/code-qtzl/post-it-board.git
cd post-it-board
npm run install:all
```

## Running the Application

1. Start the server (runs on port 3000):

```bash
cd server
npm run server
```

2. In a new terminal, start the client (runs on port 5173):

```bash
cd client
npm run dev
```

3. Open your browser to `http://localhost:5173`

## Features

-   Messages are stored in memory (no database required)
-   Real-time updates when new messages are posted
-   View all messages posted to the system
