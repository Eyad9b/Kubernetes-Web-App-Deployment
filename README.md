# Kubernetes-Web-App-Deployment
🎯 Project Goal
Deploy a scalable web application using Kubernetes with multiple replicas and load balancing

## 📌 Overview
This project demonstrates how to deploy a containerized web application using Kubernetes.
It ensures high availability by running multiple replicas and exposing the service externally.

---

## 🏗️ Architecture
- Deployment manages multiple pods
- Service exposes the application
- Load balancing distributes traffic

---

## ⚙️ Technologies Used
- Kubernetes
- Docker
- YAML

---

## 📋 Prerequisites
- Kubernetes cluster (Minikube in our case or cloud)
- kubectl installed

---

## 🚀 Implementation Steps

### Step 1: Create Deployment
Defines 3 replicas of the web application.

### Step 2: Create Service
Expose application using NodePort.

### Step 3: Apply Configuration

kubectl apply -f manifests/

Step 4: Access Application
minikube service web-service

📊 Results
- Application accessible via browser
- Load balancing across pods
- High availability achieved

🔐 Key Features
- Scalability with replicas
- Fault tolerance
- Container orchestration
