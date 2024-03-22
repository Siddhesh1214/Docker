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
