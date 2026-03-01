# 🚀 GCP AWX Automation Lab (Production-Style DevOps Project)
 
## 📌 Project Overview
This project demonstrates end-to-end infrastructure automation using:
- Ansible AWX (Automation Controller)
- Kubernetes (K3s Cluster - 3 Nodes)
- Google Cloud Platform (GCP)
- GitHub CI-style workflow
- SSH-based Infrastructure Management
 
Built as a real-world DevOps automation lab to simulate enterprise automation environments.
 
---
 
## 🏗️ Architecture
- 1 Master Node (AWX + Control Plane)
- 2 Worker Nodes (Automation Targets)
- AWX deployed on Kubernetes cluster
- Playbooks stored in GitHub and executed via AWX Job Templates
 
---
 
## ⚙️ Key Features
- Automated server provisioning using Ansible
- Docker installation automation
- Full server setup automation (Production-style)
- Git-integrated AWX project workflow
- Secure SSH credential management in AWX
- Cloud-native automation on GCP VMs
 
---
 
## 📂 Playbooks Included
### 1️⃣ install_docker.yml
Automates:
- Package updates
- Docker installation
- Service enablement
 
### 2️⃣ full_server_setup.yml
Production-grade automation that installs:
- Docker
- Git
- Curl
- Python3-pip
- Kubernetes CLI (kubectl)
- System utilities (htop, unzip)
 
---
 
## 🖥️ Tech Stack
- Ansible
- AWX (24.x)
- Kubernetes (K3s)
- Google Cloud Compute Engine
- Linux (Ubuntu 22.04)
- Git & GitHub
 
---
 
## 🎯 Real-World Use Cases
- DevOps automation for cloud servers
- Infrastructure provisioning
- Configuration management at scale
- CI/CD automation environments
- Freelance client infrastructure setup
 
---
 
## 👨‍💻 Author
DevOps Automation Engineer  
Specializing in:
- Ansible Automation
- AWX Deployment
- Cloud Infrastructure (GCP)
- Kubernetes Automation
 
