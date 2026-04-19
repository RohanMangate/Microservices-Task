\# Microservices Containerization Assessment



\## Overview

This project demonstrates containerization of a Node.js based microservices application using Docker and Docker Compose.



The application consists of three microservices:

\- User Service (Port 3000)

\- Product Service (Port 3001)

\- Gateway Service (Port 3003)



Each service is containerized using Docker and orchestrated together using Docker Compose.



\---



\## Prerequisites

\- Docker Desktop installed

\- Git installed



\---



\## Setup Instructions



### 1. Clone the repository:

```bash

git clone https://github.com/<your-username>/Microservices-Task.git

cd Microservices-Task



### 2. Build and run all services using Docker Compose:

docker-compose up --


## Testing the Services (The services can be tested using a browser)

* User Service APIs: http://localhost:3000
* Product Service APIs: http://localhost:3001
* Gateway Service APIs: http://localhost:3003

## Note: 
If the root URL (/) shows "Cannot GET /", it is expected behaviour since the services expose API endpoints and not a frontend UI.

## Troubleshooting: 
### 1. If Docker build fails: docker-compose build --no-cache
### 2. If ports are already in use: Stop any process running on ports 3000, 3001, or 3003.
### 3. To view logs: docker-compose logs

## Screenshots:
Screenshots showing running containers, Docker logs, and browser testing are attached for validation.