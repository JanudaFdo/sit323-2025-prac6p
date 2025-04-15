# SIT323/SIT737 – Cloud Native Application Development

## 🧠 Task: Creating a Kubernetes Cluster for a Containerized Node.js Application

This project demonstrates how to containerize a Node.js application and deploy it to a Kubernetes cluster using Docker, kubectl, and Kubernetes YAML configuration files.


## 📦 Technologies Used

- Node.js
- Docker
- Kubernetes (via Minikube or any other cluster)
- kubectl (Kubernetes CLI)
- Git & GitHub
- Visual Studio Code

---

## 🚀 Project Setup and Instructions

# 1️⃣ Clone the Repository
```git clone https://github.com/yourusername/sit323-2025-prac6p.git```


# 2️⃣ Build and Push Docker Image
Ensure Docker is running on your system.

```docker build -t yourusername/node-app:v1 .```
```docker login```
```docker push yourusername/node-app:v1```


# 3️⃣ Start Kubernetes Cluster
```minikube start```


# 4️⃣ Deploy Application to Kubernetes
Apply Deployment and Service Files
```kubectl apply -f deployment.yaml```
```kubectl apply -f service.yaml```


# 5️⃣ Verify the Deployment
```kubectl get pods```
```kubectl get services```



