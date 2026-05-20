# Cloud Native E-Commerce DevOps Project

A cloud-native DevOps project demonstrating modern software deployment practices using Docker, GitHub Actions, Jenkins, Kubernetes, and Render cloud deployment.

---

# Project Overview

This project simulates a cloud-native e-commerce platform consisting of multiple services and automated DevOps workflows.

The project demonstrates:

- Docker containerization
- CI/CD automation
- GitHub Actions pipelines
- Jenkins pipeline integration
- Kubernetes deployment manifests
- Render cloud deployment
- Git Flow branching strategy
- Multi-environment deployment setup

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Docker | Application containerization |
| GitHub Actions | Continuous Integration & Deployment |
| Jenkins | Automation pipeline |
| Kubernetes | Container orchestration |
| Render | Cloud hosting and deployment |
| Git & GitHub | Version control |
| HTML/CSS/JavaScript | Frontend interface |
| YAML | Kubernetes configurations |

---

# Project Architecture

The project follows a cloud-native microservices-inspired architecture.

Services included:

- Frontend Service
- User Service
- Product Service
- Order Service
- Notification Service

Each service is containerized and prepared for Kubernetes deployment.

---

# Project Structure

```text
cloud-native-ecommerce-devops/
│
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── cd.yml
│
├── src/
│   └── frontend/
│       ├── index.html
│       ├── styles.css
│       └── script.js
│
├── k8s/
│   ├── frontend-deployment.yaml
│   ├── user-deployment.yaml
│   ├── product-deployment.yaml
│   ├── order-deployment.yaml
│   └── notification-deployment.yaml
│
├── Dockerfile
├── Jenkinsfile
├── .dockerignore
├── .gitignore
└── README.md