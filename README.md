# Dockerized Nginx Web Server

## Project Overview

This project demonstrates how to deploy a static website using Nginx inside a Docker container.

## Technologies Used

- Ubuntu Linux
- Docker
- Nginx
- HTML
- Git
- GitHub

## Project Architecture

Browser → Docker Container → Nginx → HTML Website

## Dockerfile

The Dockerfile uses the official Nginx image and copies the custom HTML page into the Nginx web root.

## Build Docker Image

```bash
docker build -t ahmed-nginx-web .
