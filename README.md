# Ral-Time-Chatting-Application
 It is an scalable Realtime Chatting Application that provides an interface for multiple user chatting at the same time.
 FrontEnd Technologies- HTML, CSS
BackEnd Technologies- JavaScript, Node.js
Used Socket.io module for a two-way connection between client and server.
FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.
HTML has been used for preparing the structure of application.
CSS has been used for styling the application.
Added Client sided JavaScript for the purpose of playing with DOM elements.
First of all stored all the DOM elements in a respectives JS variable.
Used Audio file (ting.mp3) which gives notification on receiving the messages.
Everytime a new user tries to join, first of all ask his/her name and let the server know.
If a new user joins, receive the event from the server using eventListner.
Receive message from server using receive function.
If a user leaves the chat, tell all the other users that this user has left the chat.
Server Side JavaScript will handle the Socket IO connections.
If a new user joins, let the other users connected with server know.
If someone sends the message, broadcast it to other people.
If someone leaves the chat, let others know.

#What are WebSockets?
WebSockets are quite an interesting technology in and of itself. Let’s take a closer look at what it is.

#WebSocket definition
WebSockets API is a technology providing a bidirectional communication channel between a client and a server. That means that the client no longer needs to be an initiator of a transaction while requesting data from both the server and database.


#How do WebSockets work?
Typically, the client requests data starting a new connection and then the client loses connection. The server sending data also only has connection during the exchange. With WebSockets, during the first request to the backend server, except receiving incoming data, the socket.io client also establishes an initial connection. This process is known as the WebSocket handshake. 🤝 The Upgrade header is included in the request. That’s how the client connected informs the server that it needs to create a connection.
