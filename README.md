# HaloCall
HaloCall – A warm, welcoming video connection.   A video calling app using the MERN stack (MongoDB, Express.js, React, Node.js) and Socket.io enables real-time communication between users.
1. Frontend (React)
UI Components: Login, dashboard, call interface (video, audio, and chat).

WebRTC Integration: Uses WebRTC APIs to establish peer-to-peer video/audio calls.

Socket.io Client: Manages signaling for call setup and real-time chat.

Redux/Context API: Stores user and call state.

Tailwind/Material-UI: Styling and UI enhancements.

2. Backend (Node.js + Express)
Socket.io Server: Handles real-time signaling for WebRTC connections.

REST API: Manages user authentication, call history, and notifications.

JWT Authentication: Secures user sessions.

MongoDB Database: Stores user profiles, call logs, and chat history.

3. Real-Time Communication (WebRTC + Socket.io)
Peer Connections: Establishes direct media streams between users.

Signaling Mechanism: Socket.io is used for offer/answer exchange and ICE candidate sharing.

STUN/TURN Servers: Used for network traversal and ensuring connectivity.
