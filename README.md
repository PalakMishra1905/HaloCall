# HaloCall
HaloCall – A warm, welcoming video connection.   A video calling app using the MERN stack (MongoDB, Express.js, React, Node.js) and Socket.io enables real-time communication between users.

<b>1. Frontend (React)</b>

<ul>
  <li>UI Components: Login, dashboard, call interface (video, audio, and chat).</li>

  <li>WebRTC Integration: Uses WebRTC APIs to establish peer-to-peer video/audio calls.</li>

  <li>Socket.io Client: Manages signaling for call setup and real-time chat.</li>

  <li>Tailwind/Material-UI: Styling and UI enhancements.</li>
</ul>

<b>2. Backend (Node.js + Express)</b>

<ul>
  <li>Socket.io Server: Handles real-time signaling for WebRTC connections.</li>

  <li>REST API: Manages user authentication, call history, and notifications.</li>

  <li>JWT Authentication: Secures user sessions.</li>

  <li>MongoDB Database: Stores user profiles, call logs, and chat history.</li>
</ul>

<b>3. Real-Time Communication (WebRTC + Socket.io)</b>

<ul>
  <li>Peer Connections: Establishes direct media streams between users.</li>

  <li>Signaling Mechanism: Socket.io is used for offer/answer exchange and ICE candidate sharing.</li>

  <li>STUN/TURN Servers: Used for network traversal and ensuring connectivity.</li>
</ul>  
