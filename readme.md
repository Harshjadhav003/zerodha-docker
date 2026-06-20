# 🐳 Zerodha Docker Setup

Dockerized deployment setup for the Zerodha Clone microservices ecosystem.

This repository contains development and production configurations for running the Zerodha application stack using Docker and Docker Compose.

## 🚀 Services

* Backend (Node.js + Express)
* Frontend (React + Vite)
* Dashboard (React + Vite)
* Redis Cache

## 🛠️ Technologies

* Docker
* Docker Compose
* Nginx
* Node.js
* Redis

## 📂 Architecture

```text
Frontend ──┐
           │
Dashboard ─┼──► Backend API ───► MongoDB
           │
           └──► Redis Cache
```

## ⚙️ Development

Build and run all services locally:

```bash
docker compose up --build
```

## 🚀 Production

Run using pre-built Docker Hub images:

```bash
docker compose -f docker-compose.prod.yml up -d
```

## 📦 Docker Images

* docker-setup-backend
* docker-setup-frontend
* docker-setup-dashboard

## 🔗 Related Repositories

* Main Project: https://github.com/Harshjadhav003/ZERODHA
* Backend: https://github.com/Harshjadhav003/zerodha-backend
* Frontend: https://github.com/Harshjadhav003/zerodha-frontend
* Dashboard: https://github.com/Harshjadhav003/zerodha-dashboard

## 👨‍💻 Author

**Harsh Jadhav**

Full Stack Developer | MERN | Docker | System Design
