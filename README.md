# ledgar app
# Web Ledger – DevOps Dockerized Project for Kubernetes

This repository is a Dockerized version of the [web-ledger](https://github.com/fred4impact/web-ledger) project — a web-based ledger system built with Django. It was prepared as part of a DevOps project to demonstrate containerization, image publishing, and Kubernetes readiness.

---

## 🚀 Project Overview

- ✅ Django-based ledger management application
- 🐳 Containerized using Docker
- ☸️ Kubernetes-ready architecture
- 🔐 Includes default admin credentials for testing
- 📦 Image build, run, and push workflow included

---

## 🧑‍💻 Default Credentials

- **Username**: `admin`  
- **Password**: `admin`

---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/fred4impact/web-ledger.git
cd web-ledger


# Buil the Docker Image
```docker build -t your_username/web-ledger:latest .

# Run thee container locally
```
docker run -d -p 8000:8000 your_username/web-ledger:latest

# Push Docker Image to Docker Hub
``` docker login

docker push your_username/web-ledger:latest


