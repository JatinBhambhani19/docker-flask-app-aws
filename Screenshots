# 🚀 Dockerized Flask Application on AWS EC2

## 📌 Project Overview

This project demonstrates the deployment of a containerized Python Flask web application on Amazon Web Services (AWS) using Docker and Ubuntu EC2. The application is packaged into a Docker container, deployed on an AWS EC2 instance, exposed through a public IP address, and published to Docker Hub for easy distribution and deployment.

This project showcases practical skills in Cloud Computing, Docker Containerization, Linux Administration, Networking, and DevOps fundamentals.

---

## 🎯 Project Objectives

- Deploy a Python Flask application on AWS EC2.
- Containerize the application using Docker.
- Build and manage Docker images and containers.
- Configure AWS Security Groups.
- Publish Docker images to Docker Hub.
- Demonstrate cloud deployment and DevOps practices.

---

## 🏗️ Architecture

```text
User Browser
      │
      ▼
AWS EC2 Instance (Ubuntu)
      │
      ▼
Docker Engine
      │
      ▼
Docker Container
      │
      ▼
Python Flask Application
```

---

## 🛠️ Technologies Used

### Cloud Platform
- Amazon Web Services (AWS EC2)

### Containerization
- Docker
- Docker Hub

### Programming Language
- Python 3

### Framework
- Flask

### Operating System
- Ubuntu 24.04 LTS

### Networking
- Security Groups
- Public IP Access
- Port Mapping

### Version Control
- Git
- GitHub

---

## ✨ Key Features

- Dockerized Flask Application
- AWS EC2 Deployment
- Docker Image Creation and Management
- Public Web Access
- Docker Hub Integration
- Linux Server Administration
- Security Group Configuration
- Cloud Infrastructure Deployment

---

## 📂 Project Structure

```text
docker-flask-app/
│
├── app.py
├── requirements.txt
├── Dockerfile
├── screenshots/
└── README.md
```

---

## 🚀 Deployment Process

### Step 1: Launch AWS EC2 Instance

- Ubuntu 24.04 LTS
- t3.micro Instance
- Public IPv4 Enabled

### Step 2: Configure Security Groups

Inbound Rules:

| Type | Port |
|--------|--------|
| SSH | 22 |
| HTTP | 80 |
| Custom TCP | 5000 |

### Step 3: Install Docker

```bash
sudo apt update
sudo apt install docker.io -y
sudo systemctl start docker
sudo systemctl enable docker
```

### Step 4: Build Docker Image

```bash
sudo docker build -t flask-app .
```

### Step 5: Run Docker Container

```bash
sudo docker run -d -p 5000:5000 --name flask-container flask-app
```

### Step 6: Verify Running Containers

```bash
sudo docker ps
```

### Step 7: Access Application

```text
http://YOUR_PUBLIC_IP:5000
```

### Step 8: Push Image to Docker Hub

```bash
sudo docker login
sudo docker tag flask-app jatinbhambhani/flask-app:latest
sudo docker push jatinbhambhani/flask-app:latest
```

---

## 🐳 Docker Hub Repository

Docker Hub:

https://hub.docker.com/r/jatinbhambhani/flask-app

---

## 📸 Project Screenshots

### AWS EC2 Instance Running

![EC2 Running](screenshots/EC2-Running.jpeg)

### Security Group Configuration

![Security Group](screenshots/Security-Group.jpeg)

### Docker Installation

![Docker Version](screenshots/Docker-Version.jpeg)

### Docker Image Build

![Docker Build](screenshots/Docker-Build.jpeg)

### Running Docker Container

![Docker Container](screenshots/Docker-Container-Running.jpeg)

### Flask Application Output

![Flask Output](screenshots/Flask-App-Output.jpeg)

### Docker Hub Login

![Docker Login](screenshots/Docker-Hub-Login.jpeg)

### Docker Push Success

![Docker Push](screenshots/Docker-Hub-Push.jpeg)

### Docker Hub Repository

![Docker Hub Repository](screenshots/Docker-Hub-Repository.jpeg)

---

## 💻 Docker Commands Used

### Build Image

```bash
docker build -t flask-app .
```

### Run Container

```bash
docker run -d -p 5000:5000 --name flask-container flask-app
```

### View Running Containers

```bash
docker ps
```

### View Images

```bash
docker images
```

### Stop Container

```bash
docker stop flask-container
```

### Remove Container

```bash
docker rm flask-container
```

### Push Image to Docker Hub

```bash
docker push jatinbhambhani/flask-app
```

---

## 🎓 Skills Demonstrated

- AWS EC2 Administration
- Docker Containerization
- Docker Hub Registry Management
- Linux System Administration
- Python Flask Development
- Cloud Networking
- Security Group Configuration
- Application Deployment
- Infrastructure Management
- DevOps Fundamentals

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Cloud Infrastructure Deployment
- Docker Container Management
- Linux Server Administration
- Networking and Security Configuration
- Docker Hub Integration
- DevOps Deployment Workflow
- Application Hosting on AWS

---

## 🔮 Future Enhancements

- Deploy Behind Nginx Reverse Proxy
- Configure HTTPS using SSL Certificates
- Implement CI/CD using GitHub Actions
- Multi-Container Deployment with Docker Compose
- Kubernetes Deployment (EKS)

---

## 👨‍💻 Author

### Jatin Bhambhani

Master of Computer Applications (Cloud Computing)

**Skills:** AWS | Docker | Linux | Python | Flask | GitHub | DevOps

### GitHub Repository

https://github.com/JatinBhambhani19/docker-flask-app-aws

### Docker Hub Profile

https://hub.docker.com/u/jatinbhambhani
