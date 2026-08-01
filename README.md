# DevOps Complete Project - CI/CD Pipeline on AWS EC2 🚀
 
**Status:** ✅ Completed
 
---
 
# Project Overview
 
This project demonstrates an end-to-end CI/CD pipeline for a PHP web application using AWS EC2, GitHub, Docker, and Jenkins.
 
Whenever code is pushed to GitHub, Jenkins automatically detects the change, builds the application, and deploys the latest version inside a Docker container running on an AWS EC2 instance.
 
---
 
# Objectives
 
- Deploy a PHP application on AWS EC2
- Manage source code using Git and GitHub
- Containerize the application using Docker
- Automate deployment using Jenkins
- Trigger builds automatically using GitHub Webhooks
 
---
 
# Architecture
 
```
Developer
     │
     ▼
GitHub Repository
     │
     │ (Webhook)
     ▼
Jenkins
     │
     ▼
Docker Build
     │
     ▼
Docker Container
     │
     ▼
AWS EC2 Instance
     │
     ▼
PHP Web Application
```
 
---
 
# Technologies Used
 
- AWS EC2
- Ubuntu Linux
- Git
- GitHub
- GitHub Webhooks
- Docker
- Jenkins
- PHP
- Apache
- Shell Commands
 
---
 
# Project Structure
 
```
devops-complete-project/
│
├── app/
│   ├── index.php
│   └── style.css
│
├── docker/
│
├── jenkins/
│
├── screenshots/
│
├── Dockerfile
├── Jenkinsfile
├── README.md
└── .gitignore
```
 
---
 
# CI/CD Workflow
 
1. Developer pushes code to GitHub.
2. GitHub Webhook notifies Jenkins.
3. Jenkins starts the pipeline automatically.
4. Docker image is built.
5. Existing container is replaced.
6. New container is deployed.
7. Updated application becomes available on the EC2 Public IP.
 
---
 
# Features
 
- Automated CI/CD Pipeline
- Dockerized PHP Application
- Jenkins Pipeline
- GitHub Webhook Integration
- AWS EC2 Deployment
- Automatic Docker Deployment
- Version Controlled using Git
 
---
 
# Screenshots
 
The **screenshots/** folder contains project execution screenshots, including:
 
- AWS EC2 Instance
- Security Groups
- Docker Image
- Docker Container
- Jenkins Dashboard
- Jenkins Build History
- Successful Pipeline Build
- GitHub Webhook
- Website Running
- Terminal Commands
 
---
 
# Skills Demonstrated
 
- Linux Administration
- Git & GitHub
- Docker
- Jenkins
- CI/CD
- GitHub Webhooks
- AWS EC2
- Apache Web Server
- PHP Deployment
- Troubleshooting
 
---
 
# Challenges Solved
 
During this project I resolved several real-world deployment issues including:
 
- Docker port conflicts
- Apache using port 80
- Jenkins port accessibility
- AWS Security Group configuration
- GitHub Webhook automation
- Docker container recreation
- Public IP accessibility
 
---
 
# Future Improvements
 
- Kubernetes Deployment
- Terraform Infrastructure as Code
- Ansible Configuration Management
- Monitoring using Prometheus & Grafana
- Nginx Reverse Proxy
- AWS Load Balancer
 
---
 
# Author
 
**Varshitha Gowda**
 
DevOps Engineer | AWS | Docker | Jenkins | Linux
 
GitHub:
https://github.com/varshimanu
 
LinkedIn:
https://www.linkedin.com/in/varshitha-g-4b8255257
 
---
 
⭐ If you like this project, feel free to star the repository.a
