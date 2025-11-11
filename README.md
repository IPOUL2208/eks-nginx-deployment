# 🚀 Deploying NGINX on Amazon EKS (Elastic Kubernetes Service)

This project demonstrates deploying an **NGINX web server** on a managed **Amazon EKS Kubernetes cluster** using `eksctl`, `kubectl`, and AWS CLI.

---

## 🧰 Tools & Technologies
- **Amazon EKS (Elastic Kubernetes Service)**
- **AWS CLI**
- **eksctl**
- **kubectl**
- **NGINX**
- **IAM OIDC Provider**
- **CloudFormation**

---

## ⚙️ Quick Start Commands

### 1️⃣ Create EKS Cluster (Control Plane)
```bash
eksctl create cluster --name my-first-cluster --region ap-south-1 --version 1.30 --without-nodegroup
