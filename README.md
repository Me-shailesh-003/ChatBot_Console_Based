This project, ChatBot, is a simple server-side application built in Java.
It listens for incoming connections from a client on port 7777 and enables two-way real-time communication.
The server handles messages from the client and responds back, allowing for a basic chat interaction.
The server uses multithreading to manage both reading and writing operations simultaneously,
ensuring that it can continuously send and receive messages without interruption.
The server also has a graceful shutdown mechanism that terminates the connection when the client sends an "exit" command.
