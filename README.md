# TCP Client Connection

<details>
<summary><strong>Description</strong></summary>

This project demonstrates how to establish a TCP connection between a client and a server using C++. The application allows a client to connect to a remote server, send messages, and receive responses over a reliable network connection.

</details>

<details>
<summary><strong>Features</strong></summary>

- Establishes a TCP connection to a server
- Sends messages from the client to the server
- Receives responses from the server
- Handles connection errors and disconnections
- Demonstrates reliable communication using TCP
- Simple command-line interface

</details>

<details>
<summary><strong>Technologies Used</strong></summary>

- C++
- TCP/IP Networking
- Socket Programming
- Linux/Unix Networking APIs
- CMake

</details>

<details>
<summary><strong>Installation</strong></summary>

### Prerequisites

- C++17 compatible compiler
- CMake 3.16 or newer

### Build Instructions

```bash
mkdir build
cd build
cmake ..
cmake --build .
```

</details>

<details>
<summary><strong>Running the Application</strong></summary>

Start the server:

```bash
./server
```

Start the client:

```bash
./client
```

</details>

<details>
<summary><strong>How It Works</strong></summary>

1. The server listens for incoming connections.
2. The client connects using an IP address and port number.
3. Messages are exchanged over a TCP connection until either side disconnects.

</details>

<details>
<summary><strong>Lessons Learned</strong></summary>

- TCP/IP networking fundamentals
- Socket management
- Client-server architecture
- Data transmission
- Connection lifecycle management

</details>

<details>
<summary><strong>Future Improvements</strong></summary>

- Support multiple clients
- SSL/TLS encryption
- Qt GUI integration
- Authentication
- File transfers
- Enhanced logging

</details>

## Author

Garrett
