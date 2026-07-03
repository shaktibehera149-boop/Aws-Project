# AWS DevOps Project - Flask & Express Deployment

This project demonstrates the deployment of a full-stack application using AWS Cloud and DevOps tools.

## Project Overview

The application contains two services:

- Flask Backend (Python)
- Express Frontend (Node.js)

Both applications are containerized using Docker and deployed on AWS infrastructure.

## Technologies Used

- AWS EC2
- AWS ECR (Elastic Container Registry)
- Docker
- Python Flask
- Node.js Express
- Git & GitHub
- Linux

## Project Architecture

1. Source code stored in GitHub repository
2. Docker images created for Flask and Express applications
3. Images pushed to AWS ECR private repositories
4. Containers deployed and tested on AWS EC2 instances

## Docker Images

Created Docker images:

- flask-app:latest
- express-app:latest

## AWS Services

### EC2
Used as a cloud server for running and testing applications.

### ECR
Used for storing Docker container images securely.

## Deployment Steps

1. Launch EC2 instances
2. Install required packages
3. Clone GitHub repository
4. Build Docker images

```bash
docker build -t app-name .
