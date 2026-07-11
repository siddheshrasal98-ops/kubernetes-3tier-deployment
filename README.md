# Kubernetes Three-Tier Deployment

## Project Overview

This project demonstrates deploying a three-tier application on Kubernetes.

## Architecture

Frontend → Backend → MySQL Database

## Technologies

- Kubernetes
- Docker
- Nginx
- MySQL

## Project Structure

```text
kubernetes-3tier-deployment/
├── kubernetes/
│   ├── namespace.yaml
│   ├── frontend-deployment.yaml
│   ├── frontend-service.yaml
│   ├── backend-deployment.yaml
│   ├── backend-service.yaml
│   ├── mysql-deployment.yaml
│   ├── mysql-service.yaml
│   └── ingress.yaml
├── README.md
└── LICENSE
```

## Features

- Namespace isolation
- Frontend deployment
- Backend deployment
- MySQL deployment
- Kubernetes Services
- Ingress configuration

## Future Improvements

- ConfigMaps
- Kubernetes Secrets
- Persistent Volumes
- Horizontal Pod Autoscaler
- Helm Charts
- ArgoCD
- Monitoring with Prometheus & Grafana

## Author

Siddhesh Rasal
