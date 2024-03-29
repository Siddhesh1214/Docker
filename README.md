# Docker

# Hosted StudentApp 3-Tier Application with Docker Compose
```
├── Database/
│ └── Dockerfile
├── Backend/
│ └── Dockerfile
└── Frontend/
└── Dockerfile
```
### Application Overview
StudentApp consists of the following components:

- Database: MySQL database to store student information.
- Backend: Backend service to handle CRUD operations on student data.
- Frontend: Frontend interface to interact with the student data.

### Getting Started
Follow these steps to host the StudentApp application:

1. Clone the Repository:
  ```
git clone https://github.com/Siddhesh1214/Docker.git
cd Docker/Host_StudentApp_3Tier
  ```
2. Build and Run the Docker Containers:
  ```
   docker-compose up -d
  ```

3. Access the Application:

      Once the containers are up and running, you can access the StudentApp frontend interface by opening your web browser and navigating to http://localhost.

---

# Hosted 2048 Game with Docker and Nginx

Welcome to the Dockerized version of the classic 2048 game! This repository provides everything you need to quickly deploy the game using Docker and Nginx.

### About the Game
2048 is a popular single-player sliding block puzzle game. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048.

### Prerequisites

Before you start, ensure you have Docker installed on your machine. If not, you can install it by following the instructions in the [official Docker documentation](https://docs.docker.com/get-docker/).

### Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/Siddhesh1214/Docker.git
    ```

2. Navigate to the `Nginx/2048` directory:

    ```bash
    cd Docker/Nginx/2048
    ```

3. Build the Docker image:

    ```bash
    docker build -t 2048-game .
    ```

4. Run the Docker container:

    ```bash
    docker run -d -p 80:80 2048-game
    ```

5. Access the game in your web browser:

    ```
    http://localhost
    ```

### How to Play

2048 is a single-player sliding block puzzle game. The objective is to slide numbered tiles on a grid to combine them and create a tile with the number 2048. Use the arrow keys to move the tiles in the respective direction.


---

# Hosted Python Flask Application Using Docker

Welcome to the Dockerized version of the Python Flask application! This repository provides the necessary files to quickly deploy your Flask app using Docker.

## Description

This Flask application serves as a template or example for building web applications using Python Flask. It demonstrates how to containerize a Flask app with Docker for easier deployment and portability.

## Prerequisites

Before you begin, ensure you have Docker installed on your machine. If not, you can install it by following the instructions in the [official Docker documentation](https://docs.docker.com/get-docker/).

## Installation and Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/Siddhesh1214/Docker.git
    ```

2. Navigate to the `Python-Flask` directory:

    ```bash
    cd Docker/Python-Flask
    ```

3. Build the Docker image:

    ```bash
    docker build -t flask-app .
    ```

4. Run the Docker container:

    ```bash
    docker run -d -p 5000:5000 flask-app
    ```

5. Access the Flask application in your web browser:

    ```
    http://localhost:5000
    ```
---

# Hosted Node.js Chat Application Using Docker

Welcome to the Dockerized version of the Node.js chat application! This repository contains the necessary files to quickly deploy your chat application using Docker.

### Description

This Node.js chat application allows users to communicate in real-time using WebSocket technology. It's a simple and scalable solution for implementing chat functionality in web applications.

### Prerequisites

Before you begin, ensure you have Docker installed on your machine. If not, you can install it by following the instructions in the [official Docker documentation](https://docs.docker.com/get-docker/).

### Installation and Usage

1. Clone this repository:

    ```bash
    git clone https://github.com/Siddhesh1214/Docker.git
    ```

2. Navigate to the `NodeJS/nodejs-chat-app` directory:

    ```bash
    cd Docker/NodeJS/nodejs-chat-app
    ```

3. Build the Docker image:

    ```bash
    docker build -t chat-app .
    ```

4. Run the Docker container:

    ```bash
    docker run -d -p 3000:3000 chat-app
    ```

5. Access the chat application in your web browser:

    ```
    http://localhost:3000
    ```

---

