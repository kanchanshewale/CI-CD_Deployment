# Node.js CI/CD Deployment Project

## Overview
This project demonstrates a Node.js web application deployed on AWS EC2 using Docker and GitHub Actions CI/CD pipeline.

## Features
- Node.js app with Express
- Dockerized container
- GitHub Actions workflow for automatic deployment to EC2

## How to Run Locally
1. Clone the repository
2. Install dependencies: `npm install`
3. Build Docker container: `docker build -t my-nodejs-app .`
4. Run container: `docker run -d -p 80:3000 my-nodejs-app`
5. Open `http://localhost:80` in browser

## Technologies Used
- Node.js
- Express.js
- Docker
- CI/CD
- GitHub Actions
- AWS EC2 (Ubuntu 24.04 LTS)

