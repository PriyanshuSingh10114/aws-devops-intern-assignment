<div align="center">

# ☁️ AWS DevOps Internship Assignment

[![AWS](https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/ec2/)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-Web_Server-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-Hello--World-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)

---

### 👨‍💻 Developed by **Priyanshu Singh**

**B.Tech CSE**

**VIT Bhopal University**

🌐 **Live Website**

## http://13.126.132.221:80

</div>

---

# 📌 Project Overview

This project demonstrates the deployment of a static HTML website on an **AWS EC2 Ubuntu instance** using the **Nginx Web Server**.

The assignment covers:

- AWS EC2 Instance Creation
- Security Group Configuration
- SSH Connectivity
- Linux Administration
- Nginx Installation & Configuration
- Static Website Deployment
- Git & GitHub Version Control
- Docker Installation (Bonus)
- Technical Documentation

---

# 🏗 Architecture

```text
                   Internet
                       │
                       ▼
               AWS Security Group
            (Port 22 & Port 80)
                       │
                       ▼
              Ubuntu EC2 Instance
                       │
                       ▼
                 Nginx Web Server
                       │
                       ▼
               Static HTML Website
```

---

# ⚙ Tech Stack

| Technology | Purpose |
|------------|----------|
| AWS EC2 | Virtual Server |
| Ubuntu 22.04 LTS | Operating System |
| Nginx | Web Server |
| HTML5 | Static Website |
| Linux | System Administration |
| Git | Version Control |
| GitHub | Repository Hosting |
| Docker | Bonus Task |

---

# 🚀 Live Deployment

### Website URL

```text
http://13.126.132.221:80
```

---

# 📁 Project Structure

```text
aws-devops-intern-assignment
│
├── index.html
├── README.md
├── Report.pdf
└── screenshots/
```

---

# 📖 Deployment Steps

## 1️⃣ Launch AWS EC2 Instance

- Ubuntu 22.04 LTS
- t2.micro
- Security Group Created

Allowed Ports

| Port | Service |
|------|----------|
|22|SSH|
|80|HTTP|

---

## 2️⃣ Connect to EC2

```bash
ssh -i aws-key.pem ubuntu@<Public-IP>
```

---

## 3️⃣ Update Packages

```bash
sudo apt-get update

```

---

## 4️⃣ Install Nginx

```bash
sudo apt install nginx -y
```

---

## 5️⃣ Check Nginx Status

```bash
sudo systemctl status nginx
```

---

## 6️⃣ Restart Nginx

```bash
sudo systemctl restart nginx
```

---

## 7️⃣ Check System Information

Disk Usage

```bash
df -h
```

Memory

```bash
free -h
```

Running Processes

```bash
top
```

---

## 8️⃣ Deploy Website

```bash
cd /var/www/html

sudo nano index.html
```

Replace the default Nginx page with the custom HTML webpage.

Restart Nginx

```bash
sudo systemctl restart nginx
```

---

# 🐳 Docker Bonus Task

Installed Docker on the EC2 instance and verified the installation using the official Hello World container.

Installation

```bash
sudo apt install docker.io -y
```

Verification

```bash
sudo docker run hello-world
```

---

# 📷 Screenshots

- ✅ EC2 Instance Dashboard
- ✅ Security Group Configuration
- ✅ SSH Connection
- ✅ Package Update
- ✅ Nginx Installation
- ✅ Nginx Running
- ✅ Disk Usage
- ✅ Memory Usage
- ✅ Default Nginx Page
- ✅ Custom Hosted Website
- ✅ Docker Hello World

---

# 📚 Linux Commands Used

```bash
sudo apt update

sudo apt upgrade

sudo apt install nginx -y

sudo systemctl status nginx

sudo systemctl restart nginx

df -h

free -h

top

sudo docker run hello-world
```

---

# 🎯 Learning Outcomes

Through this assignment I gained practical experience with:

- AWS EC2 provisioning
- Linux System Administration
- SSH Authentication
- Security Groups
- Nginx Configuration
- Static Website Hosting
- Docker Basics
- Git & GitHub Workflow
- Technical Documentation

---

# 📌 Challenges Faced

- Configuring Security Group rules
- SSH Authentication
- Replacing the default Nginx webpage
- Configuring GitHub authentication using SSH
- Verifying Docker installation

---

# 📄 Assignment Deliverables

- ✅ EC2 Instance
- ✅ Security Group
- ✅ SSH Login
- ✅ Linux Commands
- ✅ Nginx Installation
- ✅ Website Deployment
- ✅ GitHub Repository
- ✅ Documentation
- ✅ Docker Bonus

---

# 👨‍💻 Author

**Priyanshu Singh**

B.Tech Computer Science & Engineering

VIT Bhopal University

---

<div align="center">

### ⭐ Thank you for reviewing this project ⭐

Hosted on AWS EC2 • Powered by Nginx • Version Controlled with Git & GitHub

</div>
