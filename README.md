# Socket Talk - Chat App Using Socket.io and MongoDB

A simple real-time chat application built with Node.js, Express, Socket.io, and MongoDB.  
This app supports multiple chat rooms, real-time messaging, and typing indicators.

---

## Features

- Real-time messaging using Socket.io
- Multiple chat rooms
- Store chat messages persistently with MongoDB & Mongoose
- Typing indicator to show when a user is typing

---

## Project Structure

```

.
├── README.md
├── config
│   └── database-config.js      # MongoDB connection config
├── index.js                   # Main server file
├── models
│   └── chat.js                # Mongoose chat schema/model
├── package.json
├── package-lock.json
├── public
│   ├── index.html             # Client-side HTML (simple chat interface)
│   └── script.js              # Client-side Socket.io script
└── views
└── index.ejs              # Server-rendered chat room view with EJS

````

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/chat-app-socketio.git
   cd chat-app-socketio


2. Install dependencies:

   ```bash
   npm install
   ```

3. Setup MongoDB:

   Make sure you have MongoDB installed and running locally or use a cloud MongoDB URI.
   Update the connection string in `config/database-config.js` accordingly.

4. Start the server:

   ```bash
   node index.js
   ```

5. Open your browser and navigate to:

   ```
   http://localhost:3000
   ```

---

## Usage

* Enter a room ID and username to join a chat room.
* Send messages in real-time.
* See when other users are typing.
* Chat messages are saved in MongoDB for persistence.

---

## Dependencies

* [Express](https://expressjs.com/)
* [Socket.io](https://socket.io/)
* [Mongoose](https://mongoosejs.com/)
* [EJS](https://ejs.co/)

---

## License

This project is licensed under the MIT License.

---

## Contact

For any questions or suggestions, please open an issue or contact me at \[[kushagranand12345@gmail.com](mailto:kushagranand12345@gmail.com)].


