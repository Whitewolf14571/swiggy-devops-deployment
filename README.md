# 🚀 DevOps Real-Time Project: Swiggy Clone Application Deployment

## 📌 Project Overview

This project demonstrates the deployment of a **Swiggy Clone Application** using modern DevOps tools and practices.

The project covers source-code management, CI/CD automation, containerization, infrastructure provisioning, and application security as part of an end-to-end DevOps workflow.

## 🛠️ Tools & Technologies

1. **Terraform**
   Infrastructure as Code (IaC) for provisioning infrastructure.

2. **GitHub**
   Source-code management and version control.

3. **Jenkins**
   CI/CD automation for building and deploying the application.

4. **SonarQube**
   Static code analysis and code-quality checks.

5. **OWASP Dependency-Check**
   Dependency vulnerability scanning.

6. **Trivy**
   Container and security vulnerability scanning.

7. **Docker & Docker Hub**
   Containerization and container image management.

## 🏗️ DevOps Workflow

```text
Developer
   │
   ▼
GitHub
   │
   ▼
Jenkins
   │
   ├── Build
   ├── Test
   ├── SonarQube Analysis
   ├── OWASP Dependency Check
   └── Trivy Security Scan
   │
   ▼
Docker Image
   │
   ▼
Docker Hub
   │
   ▼
Deployment Infrastructure
   │
   ▼
Swiggy Clone Application
```

## 📂 Project Structure

```text
Swiggy-DevOps-Project/
│
├── src/
├── public/
├── Dockerfile
├── Jenkinsfile
├── terraform/
├── package.json
├── package-lock.json
└── README.md
```

> The exact directory structure may vary depending on the version of the project and the deployment implementation.

## 🐳 Docker

The application is containerized using Docker.

Build the Docker image:

```bash
docker build -t swiggy-app:1.0 .
```

Run the container:

```bash
docker run -d -p 3000:3000 --name swiggy-app swiggy-app:1.0
```

Check running containers:

```bash
docker ps
```

## 🔄 CI/CD with Jenkins

Jenkins is used to automate the application delivery workflow.

The pipeline can include:

```text
GitHub Checkout
      ↓
Application Build
      ↓
Testing
      ↓
SonarQube Analysis
      ↓
OWASP Dependency Check
      ↓
Docker Build
      ↓
Trivy Scan
      ↓
Docker Image Push
      ↓
Deployment
```

## 🔐 Security

Security tools used in the project include:

### SonarQube

Used for:

* Static code analysis
* Code-quality analysis
* Identification of code issues

### OWASP Dependency-Check

Used to identify known vulnerabilities in application dependencies.

### Trivy

Used for vulnerability scanning of Docker images and other project components.

## ☁️ Infrastructure with Terraform

Terraform is used as Infrastructure as Code to automate infrastructure provisioning.

The Terraform configuration can be used to create and manage the infrastructure required for application deployment.

Example workflow:

```bash
terraform init
terraform plan
terraform apply
```

To remove Terraform-managed infrastructure:

```bash
terraform destroy
```

## 🚀 Deployment

The application can be deployed through the automated DevOps pipeline.

The overall deployment process is:

```text
Code
 ↓
GitHub
 ↓
Jenkins
 ↓
Build & Test
 ↓
Security Checks
 ↓
Docker Image
 ↓
Container Registry
 ↓
Infrastructure
 ↓
Application Deployment
```

## 👨‍💻 Author

**Pankaj Bisht**

### GitHub

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/Whitewolf14571)

**GitHub:** https://github.com/Whitewolf14571

### LinkedIn

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/pankaj-bisht-a1940a8a/)

**LinkedIn:** https://www.linkedin.com/in/pankaj-bisht-a1940a8a/

## 📚 Project Reference

This repository is based on a DevOps learning/project implementation of a Swiggy Clone application. The implementation and configuration in this repository may be modified and extended as part of my own DevOps practice.

---

## ⭐ Project Focus

This project provides hands-on practice with:

* Git & GitHub
* Jenkins CI/CD
* Docker
* Docker Hub
* Terraform
* SonarQube
* OWASP Dependency-Check
* Trivy
* DevOps automation
* Application deployment

---

> **Continuous improvement, automation, and reliable delivery are at the core of DevOps.**
