# Two-Tier Flask Application on Azure Kubernetes Service (AKS)

This project demonstrates the deployment of a **two-tier web application** consisting of a **Flask web application (frontend/API)** and a **MySQL database (backend)** on **Azure Kubernetes Service (AKS)**.

The application allows users to submit messages, which are stored in a MySQL database and displayed on the frontend.

> 🔹 This repository is based on a reference project and was extended and deployed on Azure AKS for learning and hands-on DevOps experience.

---

## 🧱 Architecture

- **Frontend / API:** Flask
- **Backend Database:** MySQL
- **Containerization:** Docker
- **Orchestration:** Kubernetes (AKS)
- **Deployment:** Helm Charts
- **Exposure:** Azure LoadBalancer

---

## 🚀 What I Implemented

- Deployed a **two-tier application** on Azure Kubernetes Service
- Created Kubernetes **Deployments and Services** for Flask and MySQL
- Used **Helm** to manage Kubernetes manifests
- Configured **service-based communication** between Flask and MySQL
- Exposed the application externally using an **Azure LoadBalancer**
- Debugged real-world issues like **service discovery and pod startup order**
- Verified the application is accessible via browser

---

## 🛠️ Technologies Used

- Flask (Python)
- MySQL
- Docker
- Kubernetes
- Helm
- Azure Kubernetes Service (AKS)

---

## 📸 Validation

- Flask and MySQL pods running successfully
- Database connectivity verified using Kubernetes service DNS
- Application accessible via external IP provided by Azure LoadBalancer

---

## 📚 Reference

This project is based on the following reference repository and was deployed and validated independently on Azure AKS:

https://github.com/LondheShubham153/two-tier-flask-app

---

## 📝 Note

This project is intended for **learning and demonstration purposes** to gain hands-on experience with **cloud-native application deployment and DevOps practices**.


## 📂 Additional Documentation

- Docker setup (local development): [README_docker.md](README_docker.md)
- Kubernetes deployment details: [README_kubernetes.md](README_kubernetes.md)

---

## Author

**Aneesh S**  
GitHub: https://github.com/aneesh-siva  
LinkedIn: www.linkedin.com/in/aneesh-siva-a958b4249


