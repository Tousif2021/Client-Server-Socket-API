# Client-Server-Socket-API
Virtual connection between a client and a server using socket method and one direction pipeline. 

This project demonstrates a basic **client-server communication model** using **sockets in C**. It shows how a client can connect to a server, send messages, and receive responses over TCP/IP.
---
## 📁 Project Structure

```
.
├── client.c          # Client-side implementation
├── server.c          # Server-side implementation
├── Makefile          # For compiling the client and server
└── README.md         # Project documentation

````
---
## ⚙️ How It Works

- The **server** creates a TCP socket, binds it to a port, listens for incoming connections, accepts a client, and responds to messages.
- The **client** connects to the server, sends messages, and receives replies.
- TCP ensures reliable and ordered communication.
  
---
## 🧰 Features

* TCP-based client-server communication
* Looping message exchange
* Simple and extendable design
* Error handling and socket cleanup

---
## 💡 Use Cases

* Basic chat app
* Multiplayer game networking
* File transfer prototype
* Backend-to-backend communication simulation
---
# Steps:
  * IP address for establishing the connection
  * Port number
  * Transport method usually TCP or UDP
