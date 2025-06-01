# REAL-TIME-CHAT-APPLICATION

COMPANY  : CODTECH IT SOLUTIONS

NAME     : PUTTA NIKHITHA

INTERN ID: CT08DM1033

DOMAIN   : MERN STACK WEB DEVELOPMENT

DURATION : 8 WEEKS

MENTOR   : NEELA SANTHOSH

# Description

This is a **Mern-stack real-time chat application** built using **React** for the frontend and **Node.js with Socket.IO** for the backend. The application allows users to send and receive messages instantly, demonstrating the use of WebSocket technology for live communication.The frontend offers a responsive interface built with React components, while the backend handles message broadcasting using Express and Socket.IO.

## 🚀 Features

- Real-time messaging using Socket.IO
- Simple, intuitive React-based UI
- Backend server built with Node.js and Express
- Easy to run locally
- Lightweight and fast


## 🛠️ Tech Stack

### Frontend:
- React
- JavaScript (ES6+)
- CSS for styling

### Backend:
- Node.js
- Express
- Socket.IO


## 📁 Folder Structure

The project is divided into two main directories: `client` and `server`.

### `client/`

This is the frontend part of the application.

- `public/` - Contains the HTML template.
  - index.html
  - favicon.ico
- `src/` - All React components and styles.
  - `App.js` - Main React component.
  - `index.js` - Entry point of the React app.
  - `App.css` / `index.css` - Styling.
  - App.test.js
  - logo.svg   -for logo
- `package.json` - Contains project dependencies and scripts.

### `server/`

This contains the backend code.

- `index.js` - Sets up the Express server and handles Socket.IO logic.
- `package.json` - Dependencies for the backend.


## ⚙️ Installation

Follow these steps to set up the project locally.

### Prerequisites:

- Node.js installed
- npm or yarn package manager
 
### 1. Clone the Repository


git clone https://github.com/puttanikhitha/REAL-TIME-CHAT-APPLICATION.git

### Backend Setup (Node.js + Socket.IO)

cd server

npm install     # Install backend dependencies

node index.js   # Start the backend server

#  Frontend Setup (React)

cd client

npm install     # Install frontend dependencies

npm start       # Start the React development server

The frontend will start on: http://localhost:3000

# ✅ Test the App

Open http://localhost:3000 in your browser.

Open another tab or window to simulate a second user.

Start chatting in real-time!

# 💬 How It Works

When a user sends a message through the React frontend, it emits a chat message event via Socket.IO.

The Node.js server listens for this event and broadcasts the message to all connected clients.

All clients receive the message in real-time and display it in the chat window.


# ✅ Future Enhancements

User authentication (e.g., JWT, OAuth)

Persistent chat storage using a database (MongoDB, PostgreSQL, etc.)

Typing indicators

Private messaging or chat rooms

User online/offline status

# Output

Below is an example of a real-time chat conversation between two friends using the application:

**Chat from Friend 1 :**
![Image](https://github.com/user-attachments/assets/bfd23f47-3b4a-4f23-b0f5-512278ad62be)

**chat form friend2:**

![Image](https://github.com/user-attachments/assets/bbc1f9ef-8fc2-44e4-b901-f2447bb2e6fd)
