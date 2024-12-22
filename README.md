# Chat Nest

**Chat Nest** is a simple real-time chat application built using **Socket.IO** and **Node.js**. The application enables users to join a chat room, send messages, and get notified when other users join or leave the chat.

## Features

- Real-time messaging using Socket.IO
- Notifications for users joining or leaving the chat
- User-friendly interface with audio notifications for new messages

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Socket.IO

## Setup Instructions

### Prerequisites

- Node.js installed on your system

### Installation Steps

1. Clone the repository or download the source code.
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install the dependencies.
   ```bash
   npm install socket.io
   ```

3. Start the Socket.IO server.
   ```bash
   node client.js
   ```

4. Open the `index.html` file in your browser to access the chat application.

## File Structure

- **client.js**: Contains the frontend logic for handling user interactions and communicating with the Socket.IO server.
- **index.js**: HTML file for the chat interface.
- **server.js**: Node.js server file that manages user connections and broadcasts messages using Socket.IO.
- **css/style.css**: Stylesheet for the chat application.

## How to Use

1. Open the application in your browser by navigating to the `index.html` file.
2. Enter your name when prompted to join the chat.
3. Type messages in the input box and press the "Send" button to chat with others in real time.

## Acknowledgments

- **Socket.IO** for enabling real-time bidirectional communication between web clients and servers.
- Online resources and communities for learning and troubleshooting during development.

## Future Enhancements

- Add user authentication for secure access.
- Improve the UI with responsive design and themes.
- Store chat history in a database.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the terms of the license.

