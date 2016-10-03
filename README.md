# Unix-Sockets-Shell-Chat
Chat server and client written with Unix sockets.

## Usage
To compile the application run “make” in the application directory. This results in two files: client and server.

### Usage: server
Run the server by typing “./server” in the application directory. The server will print incoming messages and information about connected clients.

### Usage: client
Run the client by typing “./client [server IP] [client IP] [client PORT]” in the application directory. The client will try to connect to the server with the specified IP-address and port number. Type any message and hit enter to send to the server. Type “quit” to close the connection. The client will also receive updates about new clients when they connect.
