# Docker Practice App

This project demonstrates how to containerize a simple Python application using Docker.

## 🚀 Features
- Built using Python 3.9-slim base image
- Dockerfile configuration
- Environment variable support (.env and -e flag)
- Docker image build and container run
- Tested using Docker Desktop

## 🛠️ Technologies Used
- Python
- Docker
- Docker Desktop
- GitHub

## 📦 Docker Commands Used

Build image:
docker build -t practice-app:1.0 .

Run container:
docker run -e APP_ENV=production practice-app:1.0

## 📸 Screenshots
(Screenshots of build and run output attached in repository)
