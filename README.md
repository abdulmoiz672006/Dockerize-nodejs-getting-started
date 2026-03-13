# DevOps Transformation: From Legacy Node.js to Automated Containerized Infrastructure

---

## **Project Overview**

This project demonstrates a **high-level DevOps lifecycle implementation**.
The original Node.js application was taken from an open-source repository and enhanced by implementing **containerization and deployment automation using Docker and GitHub Actions**.

My contribution focuses on transforming a traditional application deployment into a **modern DevOps-based automated infrastructure**.

---

## **Original Application Source**

The base application used in this project was taken from an existing open-source repository.

**Original Repository:**
https://github.com/example/original-nodejs-app

In this project, the application logic was **not modified**.

---

## **My Strategic Contribution**

I focused on **modernizing the deployment workflow**. Instead of manual setup, I implemented:

* **Containerization:** Standardizing the deployment to eliminate “works on my machine” issues
* **Automation:** Building a full CI/CD pipeline for zero-touch deployments
* **Orchestration:** Using Docker Compose for efficient service management
* **Infrastructure Modernization:** Transforming a legacy deployment into a container-based architecture

---

## **Technical Architecture**

### **1. The Core Stack**

* **Runtime:** Node.js & Express.js
* **Virtualization:** Docker (Alpine Linux for minimal image size)
* **Orchestration:** Docker Compose
* **CI/CD Platform:** GitHub Actions
* **Image Registry:** Docker Hub

---

### **2. Implementation Highlights**

* **Dockerfile Optimization:** Used lightweight base images and efficient layer caching
* **Automated Pipeline:** Every push to `main` triggers a build → tag → push cycle
* **Environment Isolation:** Fully decoupled application dependencies from the host system

---

## **Deployment & Usage**

### **Prerequisites**

Ensure you have the following installed:

* Docker Desktop
* Docker Compose

---

### **Quick Start (Local Setup)**

Follow these steps to start the application instantly.

**1. Clone the Repository**

```
git clone <your-repository-url>
cd <repo-name>
```

**2. Configure Environment Variables**

Edit the `.env` file and update the required variables.

**3. Launch the Application**

```
docker-compose up -d --build
```

---

### **Application Access**

After deployment, open:

```
http://localhost:5000
```

Check running containers:

```
docker ps
```

---

## **CI/CD Overview & Skills Demonstrated**

* Guaranteed **environment parity** between local development and production
* **CI/CD Pipeline** implemented using GitHub Actions for seamless delivery
* **Secure secret management** and environment variables for Docker Hub
* **Image versioning strategy** using proper Docker tags
* **Automated Build → Test → Registry pipeline** for high-speed deployments

---

## **Let's Connect**
* Email Me at : abdulmoizraajput@gmail.com

---

**Crafted as part of a DevOps-focused learning journey to practice containerization, automation, and modern deployment workflows.**
