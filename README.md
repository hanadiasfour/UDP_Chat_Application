# UDP Chat Application in Java

## Problem 
The challenge was to create a network communication system where multiple clients (peers) can exchange messages with each other through a central server. The server should handle message broadcasting and maintain a log of received messages.

## Solution Methodology
- Server: A UDP server that listens on port 5051, accepts incoming messages, and broadcasts them to all connected clients except the sender.
- Client: A UDP client that can send messages to the server and receive broadcast messages from the server.
- Message Handling: Messages include the sender's first and last name, and the message content. Clients display received messages along with sender information and timestamp.
