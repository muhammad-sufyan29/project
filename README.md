# DevOps CI/CD Pipeline Project

## 📌 Overview
This project is part of the **DevOps semester course** at COMSATS University, Attock Campus. The objective is to demonstrate a complete **CI/CD pipeline** using **Jenkins**, **GitHub**, and **AWS EC2**.

The pipeline:
- Automatically pulls code from GitHub when pushed
- Simulates build/test steps
- Deploys the updated application to an EC2-hosted Apache web server

---

## ⚙️ Tech Stack
- **Jenkins** – CI/CD server
- **AWS EC2 (Ubuntu 22.04)** – Deployment target
- **Apache2** – Web server
- **Git & GitHub** – Version control
- **Shell Script** – Deployment automation

---

## 🚀 CI/CD Pipeline Steps

1. **Developer pushes code** to GitHub repository.
2. **GitHub webhook triggers Jenkins** job.
3. Jenkins job:
   - Pulls the latest code
   - Simulates build/test
   - Copies code to EC2's Apache web directory (`/var/www/html/`)
4. The updated application is accessible via the EC2 public IP.

---

## 🔧 Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/muhammad-sufyan29/project.git
