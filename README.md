TCP Client Connection
Description
This project demonstrates how to establish a TCP connection between a client and a server using C++. The application allows a client to connect to a remote server, send messages, and receive responses over a reliable network connection.
Features
• Establishes a TCP connection to a server
• Sends messages from the client to the server
• Receives responses from the server
• Handles connection errors and disconnections
• Demonstrates reliable communication using TCP
• Simple command-line interface
Technologies Used
C++, TCP/IP Networking, Socket Programming, Linux/Unix Networking APIs, CMake
Installation
Prerequisites: C++17 compatible compiler, CMake 3.16 or newer.

Build Instructions:
mkdir build
cd build
cmake ..
cmake --build .
Running the Application
Start the server: ./server
Start the client: ./client
How It Works
The server listens for incoming connections. The client connects using an IP address and port number. Messages are exchanged over a TCP connection until either side disconnects.
Lessons Learned
TCP/IP networking fundamentals, socket management, client-server architecture, data transmission, and connection lifecycle management.
Future Improvements
Support multiple clients, SSL/TLS encryption, Qt GUI integration, authentication, file transfers, and enhanced logging.
Author
Garrett

