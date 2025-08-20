

##  [Chat Room]

### Overview
A lightweight chat room application written in **C++**, using **Boost.Asio** for asynchronous communication and **multi-threading** for handling multiple clients concurrently.

### Features
- **Asynchronous I/O** – Non-blocking message handling with Boost.Asio  
- **Multi-threading** – Concurrent client connections  
- **Room Management** – Add/remove clients & broadcast messages  
- **Message Handling** – Encode, decode, and deliver chat messages  

### Components
- **Session** – Manages communication for each client  
- **Room** – Tracks participants and broadcasts messages  
- **Message** – Encodes/decodes headers & bodies  
- **Server / Client** – Entry points for hosting & joining  

<img width="1340" height="435" alt="Screenshot 2025-08-19 215018" src="https://github.com/user-attachments/assets/4c67b783-db09-48a1-a813-a3169b8bcfcf" />

---

##  [Web Server](#multi-threaded-proxy-server)

### Overview
A **C-based proxy server** that supports both **with and without cache** modes. It leverages **threads, semaphores, and locks** to handle concurrent requests, while using an **LRU cache** to optimize response times.

### Features
- **Multi-threading** – Concurrent client request handling  
- **Semaphore-based Synchronization** – Safer than condition variables  
- **Caching (LRU)** – Faster responses for repeated requests  
- **Proxy Capabilities** – Request filtering, IP masking, reduced load  

### OS Concepts Used
- Threads  
- Locks  
- Semaphores  
- Cache (LRU)  

### Limitations
- Fixed cache size (large sites may not be stored)  
- Same URL with multiple clients can cause cache inconsistency  

<img width="1327" height="424" alt="Screenshot 2025-08-19 175549" src="https://github.com/user-attachments/assets/33181324-5e4e-442c-83fc-1b5a29a655ae" />


---
