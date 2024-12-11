# Web-Based-Chat-Application-uisng-Diffie-Hellman-Algorithm
This is a real-time chat application built with React, Node.js, Express, and MySQL. It features user authentication, message sending, and encryption using the Diffie-Hellman algorithm for secure key exchange between users. The application ensures that messages are exchanged securely by generating shared secrets for each communication session.

Key Features:
User Authentication: Users can register and log in to the chat application.
Real-Time Messaging: Chat messages are sent and received in real-time using Socket.IO.
Diffie-Hellman Key Exchange: Ensures secure communication by performing a Diffie-Hellman key exchange between two users, providing a shared secret for encrypting messages.
MongoDB Database: User credentials, messages, and chat data are stored in a MongoDB database for persistence.
Secure Communication: Messages are encrypted using the shared secret generated via Diffie-Hellman, ensuring privacy and security.

Technologies Used:
Frontend: React.js, Vite
Backend: Node.js, Express
Database: MongoDB
Real-Time Communication: Socket.IO
Encryption: Diffie-Hellman Key Exchange Algorithm

Future Enhancements:
Adding support for group chats.
Implementing chat history retrieval and message persistence.
Improving the user interface and UX.
