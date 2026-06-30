# 🚀 Visitor Counter Web App - Local Deployment

A basic microservices-based web application that displays a real-time visitor counter. 
This project was built as part of mastering DevOps, Linux, and containerization practices.

## 🏗️ System Architecture
The project consists of two core components isolated in separate containers, communicating over a private Docker network:
1. **Web App (Frontend/Backend):** A Python Flask web server that handles user HTTP requests.
2. **Database:** An In-Memory Redis database that stores the visitor count and performs fast incremental (`INCR`) operations.

---

## 🛠️ Prerequisites
* Docker Desktop installed and running.
* A CLI tool (such as PowerShell, Bash, or the built-in PyCharm Terminal).

---

## 🚀 Local Deployment Instructions

1. **Navigate to the project directory:**
   ```bash
   cd ./visitor-counter.App
