# Client-Server Communication with Rock-Paper-Scissors Game

This repository contains C code for a simple client-server communication system along with an implementation of a rock-paper-scissors game. The system supports basic chatting, file transfer, and interactive gameplay.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Server](#server)
  - [Client](#client)
- [Usage](#usage)
- [Game Instructions](#game-instructions)
- [File Transfer](#file-transfer)
- [Chatting](#chatting)
- [Exit Program](#exit-program)
- [License](#license)

## Features

1. **Rock-Paper-Scissors Game:** Play a simple rock-paper-scissors game with the server.

2. **File Transfer:** Send files from the client to the server.

3. **Chatting:** Engage in real-time chat between the client and the server.

4. **Graceful Program Exit:** Close the connection and exit the program smoothly.

## Prerequisites

- C compiler (e.g., GCC)
- Basic understanding of C programming

## Getting Started

### Server

1. Compile the server code:

   ```bash
   gcc server.c -o server -pthread
   ```

2. Run the server:

   ```bash
   ./server
   ```

### Client

1. Compile the client code:

   ```bash
   gcc client.c -o client -pthread
   ```

2. Run the client:

   ```bash
   ./client
   ```

## Usage

Choose an option from the menu:

1. Chatting with the server
2. Sending files to the server
3. Exit program
4. Play Rock-Paper-Scissors with the server

## Game Instructions

1. Enter your move:
   - `0` for Rock 🪨
   - `1` for Paper 📄
   - `2` for Scissors ✂️
   - `-1` to exit the game

2. View the server's move and the game result.

## File Transfer

1. Enter the path of the file to transfer.

2. The server will receive the file.

## Chatting

1. Type your message and press Enter to send it to the server.

2. Type "exit" to close the connection and exit the program.

## Exit Program

Choose option `3` to exit the program gracefully.

## License

This project is licensed under the [MIT License](LICENSE).
