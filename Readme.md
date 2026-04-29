# Docker CI/CD Lab

A complete CI/CD pipeline built with GitLab CI/CD for a Node.js application,
demonstrating real-world DevOps practices.

## Pipeline Stages

- **Build** — Docker image build and push to GitLab Container Registry
- **Test** — Application health checks and npm test suite
- **Security** — Trivy vulnerability scanning with CRITICAL CVE blocking
- **Deploy** — Manual approval gates for staging and production environments

## Tech Stack

- Docker & Docker Compose
- GitLab CI/CD
- Trivy (Aqua Security)
- Node.js / Express
- MongoDB, Redis, Nginx

## Features

- Multi-environment support (staging / production)
- Container vulnerability scanning with CVE reporting
- GitLab Security Dashboard integration
- Slack webhook notifications
- Protected secrets management
- Non-root container security
- Health check monitoring

## Author

Tahoor Ali Shah — DevOps & Cloud Engineer
