# DevOps CI/CD Pipeline on AWS

This project demonstrates a complete DevOps pipeline using modern cloud and automation tools.

## Tools Used

- AWS EC2
- Docker
- Kubernetes
- Jenkins
- Prometheus
- Grafana

## Architecture

Developer → GitHub → Jenkins → Docker Build → DockerHub → Kubernetes → Monitoring

## Features

- Automated CI/CD pipeline
- Containerized application
- Kubernetes deployment
- Infrastructure monitoring
- Scalable cloud architecture

## Deployment Flow

1. Developer pushes code to GitHub
2. Jenkins triggers CI/CD pipeline
3. Docker image is built and pushed to DockerHub
4. Kubernetes deploys the application
5. Prometheus and Grafana monitor infrastructure
