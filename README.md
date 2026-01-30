🎮 2048 Game Deployment on AWS EKS

This project demonstrates the end-to-end deployment of the open-source 2048 game on AWS Elastic Kubernetes Service (EKS) using Docker, Amazon ECR, and Kubernetes.

The focus of this project is DevOps and cloud infrastructure, including containerization, orchestration, deployment, and secure Git practices.


🚀 Tech Stack

Docker – Containerization

Amazon ECR – Container image registry

Amazon EKS – Managed Kubernetes cluster

Kubernetes – Deployment & Service (LoadBalancer)

AWS Elastic Load Balancer – Public access

Git & GitHub – Version control & documentation


🏗️ Architecture

User (Browser)
   ↓
AWS Elastic Load Balancer
   ↓
Kubernetes Service (LoadBalancer)
   ↓
Kubernetes Pods (Deployment – 2 replicas)
   ↓
NGINX Container
   ↓
2048 Game Application


⚙️ Deployment Workflow

Dockerized the 2048 web application

Pushed Docker image to Amazon ECR

Created an EKS cluster using eksctl

Deployed the application using Kubernetes Deployment

Exposed the application using a LoadBalancer Service

Performed rolling updates after application changes


🎮 Application Output

The application was successfully deployed and accessed via an AWS LoadBalancer URL.

Deployed on AWS EKS by Alex Selvin
