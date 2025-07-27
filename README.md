# Transforming a Go Web Application with DevOps Practices
# Project Overview:

This project focused on applying advanced DevOps practices to a simple Go web application built with the net/http package. The main objectives were to containerize the application, automate infrastructure provisioning, and establish a robust CI/CD pipeline for streamlined deployment and monitoring.

Key activities included:

Creating a multi-stage, distroless Dockerfile to build secure and lightweight container images.

Using Terraform to provision AWS infrastructure, including an EKS Kubernetes cluster.

Developing Kubernetes manifests and Helm charts for managing deployments, services, and ingress resources.

Setting up an NGINX ingress controller to manage HTTP routing.

Implementing automated CI/CD pipelines with GitHub Actions for build, test, and deployment automation.

Applying GitOps principles through ArgoCD for continuous delivery.

Integrating Prometheus and Grafana for monitoring and visualization of application and cluster metrics.

Managing the project using Agile Scrum methodologies within Jira for efficient delivery and iteration.

# Project Structure:
.
├── .github

│   └── workflows

│       └── ci-cd.yml

├── go-web-app/

│   ├── main.go

│   └── ...

├── helm/

│   └── go-web-app/

│       ├── Chart.yaml

│       ├── values.yaml

│       └── templates/

├── kubernetes/

│   ├── deployment.yaml

│   └── service.yaml

├── terraform/

│   ├── main.tf

│   ├── variables.tf

│   └── outputs.tf

├── Dockerfile

└── README.md

# More Detail...

# Containerization with Docker
[ArgoCD Dashboard](./screenshots/Docker)

