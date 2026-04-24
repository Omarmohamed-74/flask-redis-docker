# 🐳 Flask Visitor Counter (Dockerized)

A simple containerized web application built with Flask and Redis to count website visitors. The project is deployed on an AWS EC2 instance using Docker Compose.

---

## 🚀 Tech Stack

* Flask (Python web framework)
* Redis (in-memory data store)
* Docker (container platform)
* Docker Compose (multi-container orchestration tool)
* AWS EC2 (Linux instance)

---

## 📦 Project Structure

```
.
├── app.py
├── requirements.txt
├── Dockerfile
├── docker-compose.yml
└── README.md
```

---

## ⚙️ How It Works

* Flask app runs as a web server
* Redis stores the visitor count
* Every request increases the counter
* The current count is returned to the user

---

## 🛠️ Run Locally

### 1. Clone the repo

```bash
git clone <repo-link>
cd <project-folder>
```

### 2. Run with Docker Compose

```bash
docker-compose up --build
```

### 3. Open in browser

```
http://localhost:5000
```

---

## ☁️ Deployment

* Deployed on AWS EC2 instance
* Managed using Docker Compose for multi-container setup
* Exposed Flask app via EC2 public IP

---

## 📊 Features

* Simple visitor counter
* Fast in-memory storage using Redis
* Containerized microservices architecture
* Cloud deployment ready

---

## 👨‍💻 Author

Omar Mohamed
