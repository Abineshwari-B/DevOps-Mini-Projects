# Web Application Deployment Project

## About This Project
This project demonstrates the **end-to-end deployment of a frontend web application on AWS** using a **containerized and scalable architecture**. The primary objective is to showcase how a **static web application** can be packaged into a Docker container, stored in a **private container registry**, and deployed using **AWS managed services**, without relying on Docker Desktop on a local machine.

The **frontend source code** is stored in a separate **Source Code** folder within this GitHub repository and was **cloned from GitHub** for deployment purposes. The focus of this project is on **deployment, infrastructure setup, and container orchestration**, rather than frontend development.

The application is built and deployed using an **Amazon EC2 instance as a Docker build environment**, pushed to **Amazon ECR**, and executed on **Amazon ECS (Fargate)** behind an **Application Load Balancer (ALB)** to ensure **high availability and scalability**.

---

## Project Objectives
This project is ideal for:

- Understanding real-world web application deployment workflows  
- Practicing Docker and container-based deployments  
- Learning AWS ECS, ECR, ALB, and VPC integration  
- Demonstrating DevOps and cloud deployment skills  

---

## Tech Stack Used

### Frontend
- HTML  
- CSS  
- JavaScript  
- Bootstrap  

### DevOps & Cloud
- Docker – Application containerization  
- GitHub – Source code hosting and repository cloning  
- Amazon EC2 – Docker image build server  
- Amazon ECR – Private container image registry  
- Amazon ECS (Fargate) – Serverless container orchestration  
- Application Load Balancer (ALB) – Traffic routing and health checks  
- AWS VPC & Security Groups – Networking and access control  
- AWS CLI – Resource management and Docker image push  

---

## Project Architecture (High Level)

GitHub Repository
↓
EC2 (Docker Build Server)
↓
Docker Image
↓
Amazon ECR
↓
Amazon ECS (Fargate)
↓
Application Load Balancer
↓
Public Web Access


---

## Source Code Usage
The frontend source code is **cloned from this GitHub repository** and used solely for deployment and infrastructure demonstration. Users are free to clone the repository and reuse the source code for **learning, practice, or deployment exercises**.

---

## Notes
- This project focuses on **DevOps and AWS deployment**, not frontend development.
- Designed for **learning, demonstration, and hands-on practice**.
