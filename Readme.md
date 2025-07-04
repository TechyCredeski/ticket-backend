# 🎟️ Ticket Backend API

This is a Dockerized Node.js + TypeScript backend API for a ticketing system, powered by Express and PostgreSQL. It uses Docker Compose to orchestrate the app and database containers.

---

## 📦 Features

- Node.js 18.x + TypeScript
- Express.js server
- PostgreSQL 13 for data persistence
- Nodemon for hot-reloading in development
- Docker + Docker Compose setup
- Linting via ESLint

---

## 🚀 Getting Started

### 📁 Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/install/)

---

### 🧱 Build and Run the Containers

From the root directory, run:

```bash
docker-compose up --build
```

### 📦 NPM Scripts
| Command         | Description               |
| --------------- | ------------------------- |
| `npm run dev`   | Start server with Nodemon |
| `npm run build` | Compile TypeScript        |
| `npm start`     | Start compiled JS server  |
| `npm run lint`  | Run ESLint check          |

### 👤 Authors
Built by @oluwaseun-demonflowne

Dockerised by @TechyCredeski