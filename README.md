# Socket Programming-Based Messenger Application

## Overview
This is a real-time chat application built using Socket Programming in Android. The app allows users to send and receive messages instantly by leveraging WebSockets. It features user authentication, real-time message updates, and a clean UI for a seamless chatting experience.

## Features
- **Real-time Messaging:** Instant message delivery using WebSockets.
- **User Authentication:** Secure login and signup.
- **Chat Rooms:** Users can join different chat rooms.
- **Message History:** Displays previous messages.
- **Typing Indicator:** Shows when another user is typing.
- **Online/Offline Status:** Indicates the user’s availability.
- **Push Notifications:** Notifies users of new messages.

## Tech Stack
- **Frontend:** Kotlin, XML (UI Design)
- **Backend:** Node.js with Socket.io (for real-time communication)
- **Database:** Firebase Firestore / MySQL (for user authentication and chat history)
- **WebSocket Library:** OkHttp WebSocket for Android

## Installation
### Prerequisites
- Android Studio (Latest version)
- Node.js and npm installed (for backend setup)
- Firebase account (if using Firebase for authentication and database)

### Steps to Setup the Project
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/socket-chat-app.git
   cd socket-chat-app
   ```

2. **Backend Setup**
   - Navigate to the `server` directory:
     ```sh
     cd server
     ```
   - Install dependencies:
     ```sh
     npm install
     ```
   - Start the server:
     ```sh
     node server.js
     ```
   - Ensure the WebSocket server is running on `ws://your-server-ip:port`.

3. **Android App Setup**
   - Open the project in Android Studio.
   - Update `BASE_URL` in `Constants.kt` to match your backend WebSocket server.
   - Sync Gradle dependencies.
   - Run the app on an emulator or a physical device.

## Usage
1. Register or log in with your credentials.
2. Join a chat room or start a direct conversation.
3. Send and receive messages in real-time.
4. View message history and user status.
5. Receive notifications for new messages.

## API Endpoints (Backend)
| Endpoint          | Method | Description |
|------------------|--------|-------------|
| `/register`      | POST   | Register a new user |
| `/login`         | POST   | User login |
| `/chat/send`     | POST   | Send a new message |
| `/chat/history`  | GET    | Retrieve chat history |

## Contribution
1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature-branch-name
   ```
3. Make changes and commit:
   ```sh
   git commit -m "Add new feature"
   ```
4. Push to your forked repo and create a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For queries, feel free to reach out at:
- Email: namansinghjan2003@gmail.com
- GitHub: [your-username](https://github.com/Naman-2003)

