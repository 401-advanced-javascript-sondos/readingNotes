## Sockets
* Sockets have traditionally been the solution around which most real-time chat systems are architected, providing a bi-directional communication channel between a client and a server.

## Integrating Socket.IO
Socket.IO is composed of two parts:
1. A server that integrates with (or mounts on) the Node.JS HTTP Server socket.io
2. A client library that loads on the browser side socket.io-client



## Message Queues
* Within each Namespace, you can define arbitrary channels called “Rooms” that sockets can join and leave.


1. What does it mean that web sockets are bidirectional? Why is this useful?
- WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.  An important consequence is that you may efficiently push data from the server to the client.
2. Does socket.io use HTTP? Why?
- Socket.io uses the WebSocket Protocol instead of HTTP because it allows for real time data transfer.
3. What happens when a client emits an event?
- THE SERVER WILL LESTIN AND SEND IT TO CLIENTS
4. What happens when a server emits an event?
- all clinets will listen

### Term
* Web Socket :is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.
* Socket.io : is a library that enables real-time, bidirectional and event-based communication between the browser and the server. 
* Client : a computer or a program that, as part of its operation, relies on sending a request to another program or a computer hardware or software that accesses a service made available by a server (which may or may not be located on another computer).
* Server : a piece of computer hardware or software (computer program) that provides functionality for other programs or devices, called "clients"

