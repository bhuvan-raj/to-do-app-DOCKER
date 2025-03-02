# To-Do App (Dockerized)

## Overview
This is a simple To-Do web application with a backend built using Node.js and Express and a frontend built using React. The entire project is containerized using Docker for easy deployment.

## Features
- Add, edit, and delete tasks
- Store tasks using MongoDB
- RESTful API with Express.js
- Fully containerized using Docker

## Technologies Used
- **Frontend**: React
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Containerization**: Docker, Docker Compose

## Prerequisites
Ensure you have the following installed:
- Docker & Docker Compose
- Node.js & npm (for local development)

## Installation & Usage
### 1. Clone the Repository
```sh
$ git clone https://github.com/bhuvan-raj/to-do-app-DOCKER.git
$ cd to-do-app-DOCKER
```

### 2. Start the Application with Docker Compose
```sh
$ docker-compose up --build
```
This command will build and run the backend, frontend, and MongoDB containers.

### 3. Access the Application
Once the containers are running, open your browser and go to:
- **Frontend**: `http://localhost:3000`
- **Backend API**: `http://localhost:5000`

## Project Structure
```
/to-do-app-DOCKER
│── backend/               # Backend source code
│   ├── server.js          # Express server
│   ├── models/            # MongoDB models
│   ├── routes/            # API routes
│   ├── Dockerfile         # Docker setup for backend
│── frontend/              # Frontend source code
│   ├── src/               # React components
│   ├── public/            # Static files
│   ├── Dockerfile         # Docker setup for frontend
│── docker-compose.yml     # Docker Compose setup
│── README.md              # Project documentation
```

## Contributors
- **Bhuvan Raj** - [GitHub Profile](https://github.com/bhuvan-raj)

## License
This project is licensed under the Apache-2.0 License.

