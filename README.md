Dockerized Node.js Application with CI/CD

This repository demonstrates how a Node.js web application can be containerized and deployed using Docker, Docker Compose, and GitHub Actions CI/CD.

The original application was taken from an open-source repository and enhanced with DevOps practices, including containerization and automated deployment.

Original Project

Base Application: Node.js Getting Started App
Original Repository: https://github.com/heroku/node-js-getting-started

The original project contains the core Node.js application logic.
My contribution focuses on Dockerization and CI/CD implementation.

What I Implemented
Dockerization

Created a Dockerfile to containerize the Node.js application

Used a lightweight Node Alpine base image

Installed dependencies using npm install

Exposed the application port for container access

Docker Compose

Created a docker-compose.yml file

Configured container networking and port mapping

Simplified application startup using a single command

CI/CD Pipeline

Implemented GitHub Actions to automate the workflow.

The pipeline automatically:

Builds the Docker image

Pushes the image to Docker Hub

Deploys the updated container to the server

This enables continuous integration and deployment whenever code is pushed.

Technology Stack

Node.js

Express.js

Docker

Docker Compose

GitHub Actions (CI/CD)

Project Structure
.
├── .github/
│   └── workflows/
│       └── cicd.yml
├── Dockerfile
├── docker-compose.yml
├── index.js
├── package.json
├── package-lock.json
└── README.md


Running the Application:
Build and start containers
docker-compose build
docker-compose up -d
Access the application
http://localhost:5000

If deployed on a server:

http://<SERVER_PUBLIC_IP>:5000
Key Learnings

Dockerizing an existing application

Writing an optimized Dockerfile

Using Docker Compose for container management

Implementing CI/CD with GitHub Actions

Automating container build and deployment workflows

Notes

This project is part of my DevOps learning journey, where I focus on applying real-world DevOps tools and workflows to existing applications.
