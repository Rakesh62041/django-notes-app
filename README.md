# Automated Django Notes Application Deployment

## Project Overview

This project demonstrates automated deployment of a Django Notes Application using Docker, Docker Compose, Jenkins CI/CD pipeline, Nginx and MySQL.

## Technologies Used

- Python
- Django
- Docker
- Docker Compose
- Jenkins
- Nginx
- MySQL
- Git & GitHub

## Architecture

Developer → GitHub → Jenkins → Docker → Django + MySQL + Nginx

## Features

- User Authentication
- Notes CRUD Operations
- Dockerized Deployment
- Jenkins CI/CD Pipeline
- Nginx Reverse Proxy
- MySQL Database

## Project Structure

```bash
django-notes-app/
├── Dockerfile
├── docker-compose.yml
├── Jenkinsfile
├── nginx/
├── notesapp/
├── requirements.txt
└── README.md
