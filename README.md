# Chatroom Server

A Java-based chatroom server that allows users to create private chatrooms, invite others using randomly generated room codes, and communicate easily.

## The Problem

Messaging platforms often require users to create accounts and provide a lot of information before they can join groups and communicate with others. This can discourage new users, especially people who do not already use that platform.

The goal of this project is to create a simple chatroom server that makes connecting with others easier by allowing users to create private chatrooms and invite others using randomly generated room codes.

## How It Works

The server allows multiple clients to connect and communicate through private chatrooms.

- Users can register and log in using usernames and passwords.
- Users can create private chatrooms with randomly generated room codes.
- Other users can join chatrooms using those room codes.
- Users can send and receive messages in chatrooms.
- The server manages multiple users and chatrooms simultaneously.

![System Diagram](docs/System%20Diagram.png)

## Tech Stack

- **Programming Language:** Java
- **Libraries and Packages (Built into Java):**
  - `java.net.*` – Network and socket communication.
  - `java.io.ObjectInputStream` and `java.io.ObjectOutputStream` – Sending and receiving data.
  - `java.io.BufferedReader` and `java.io.BufferedWriter` – Reading and writing text.
  - `java.io.FileReader` and `java.io.FileWriter` – Reading and writing files.
  - `java.lang.Thread` – Handling multiple simultaneous client connections.
  - `java.util.ArrayList` – Managing users and chatroom members.
  - `java.util.Random` – Generating room codes.
  - `java.time.*` – Date and time formatting.
- **Data Storage:** `.txt` file for storing usernames, passwords, and display names.

## Setup

Instructions for setting up and running the project will be added later.

## Usage

Instructions and examples for using the chatroom server will be added later.

## Roadmap

- [ ] Direct messaging between users.
- [ ] Room owner permissions, including kicking and banning members.
- [ ] Password protection for chatrooms.

## Author

Your Name - [GitHub Profile](https://github.com/vineetparmar64)
