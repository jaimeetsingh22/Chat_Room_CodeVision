# React Chat Room App with Node.js Backend

This is a simple chat room application built with React for the frontend and Node.js for the backend. It utilizes Socket.IO for real-time messaging functionality.

## Features

- Real-time messaging: Users can send and receive messages instantly without the need to refresh the page using socket.io client and socket.io
- Multiple chat rooms: Users can join different chat rooms and engage in separate conversations.
- User authentication: Implement user authentication to allow users to log in and participate in the chat.

## Installation

1. Clone the repository:

bash
git clone https://github.com/jaimeetsingh22/Chat_Room_CodeVision


2. Navigate into the project directory:

bash
cd Chat_Room_CodeVision

3. Install dependencies for both frontend and backend:

bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd Chat_Room_CodeVision
npm install


## Usage

1. Start the backend server:

bash
cd Chat_Room_CodeVision
npm run server


This will start the Node.js server at `http://localhost:5000`.

2. Start the React frontend:

bash
cd frontent
npm run dev


This will launch the React app in your default web browser at `http://localhost:3000`.

3. Open multiple browser windows or tabs to test the real-time messaging functionality.

## Technologies Used

- React: Frontend JavaScript library for building user interfaces.
- Node.js: JavaScript runtime for building scalable network applications.
- Express.js: Web application framework for Node.js.
- Socket.IO: JavaScript library for real-time web applications, enabling bidirectional communication between web clients and servers.
- Other dependencies: Refer to the `package.json` files in the `frontend` and `backend` directories for a list of all dependencies used.

## License

This project is licensed under the [Kanishka & Jaimeet industries](LICENSE).
