# ITT440-Lab4
Socket programming in C

CHAT PROGRAM
************
-chatServer.c
-chatClient.c
************

WHAT IS IT?
A simple program that uses TCP connection and sockets to establish a 2-way text-based communication between Server and Client.

HOW TO USE?
1. Configure static ip address on both server and client hosts
2. Compile and run chatServer.c
4. Compile and run chatClient.c
5. Input the IP address of the server
6. The server host has to send a response or type [exit] to cut off the connection
7. The client host can now reply
8. The server host can type [exit] or the client host can use [CTRL+C] to close the connection

WHY IS IT NOT WORKING FOR ME?
Check the IP addresses on both hosts. For server side not being able to bind socket, simply wait for a few seconds (more details in chatServer.c).
