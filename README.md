# Docker Nginx Web Server

## 📌 Overview

This project demonstrates how to deploy an Nginx web server using Docker.

## 🛠️ Technologies Used

- Docker
- Nginx
- Linux
- HTML
- Git & GitHub

## 🚀 What I Did

- Installed Docker on Ubuntu
- Created an Nginx web server container
- Configured port mapping
- Hosted a web page using Nginx
- Accessed the application through the browser

## ⚙️ Docker Commands

```bash
docker build -t nginx-webserver .
docker run -d -p 8081:80 nginx-webserver
docker ps
docker stop <container_id>
## 🌐 Website Access

Open in your browser:

```text
http://localhost:8081
