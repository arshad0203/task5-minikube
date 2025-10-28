\# 🧩 Task 5 — Deploy an Application on Kubernetes (Minikube)



\## 📘 Objective

Set up a local Kubernetes cluster using \*\*Minikube\*\*, deploy an application using a \*\*Deployment\*\* and \*\*Service\*\*, verify it with commands, scale the app, perform a rolling update, and capture screenshots as proof.



---



\## ⚙️ Tools Used

\- Docker Desktop (Backend for Minikube)

\- Minikube v1.36.0  

\- kubectl (latest client)  

\- Windows 11 PowerShell 7.5.4



---



\## 🪜 Step-by-Step Procedure



\### 1️⃣ Start Minikube

```powershell

minikube start --driver=docker

kubectl get nodes

kubectl cluster-info



