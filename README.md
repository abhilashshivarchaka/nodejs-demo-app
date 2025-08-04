# Trigger CI
# fix push access
# Node.js Demo App – CI/CD with GitHub Actions & Docker

## 📌 Objective
Automate code deployment using CI/CD pipeline with GitHub Actions for a Node.js web app.

## 🧰 Tech Stack
- Node.js
- Docker
- GitHub Actions

## 🚀 CI/CD Workflow
On every push to `main`:
1. Checkout code from GitHub
2. Log in to DockerHub securely using secrets
3. Build Docker image
4. Push image to DockerHub: `abhilash29/nodejs-demo-app:latest`

## 🔐 GitHub Secrets Used
- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`

## 🐳 DockerHub Link
[View Image on Docker Hub](https://hub.docker.com/r/abhilash29/nodejs-demo-app)

## ✅ Result
CI/CD pipeline set up successfully. Image is automatically built and pushed on every code update.
