# AWS-Project-by-Mariam
Show Case of my Project
# 🚀 2-Tier WordPress Architecture on AWS

## 📌 Project Overview
This project demonstrates the deployment of a scalable WordPress application using a 2-tier architecture on AWS.

The architecture separates the web and database layers to improve security, scalability, and performance.

---

## 🧰 Technologies Used

### ☁️ AWS Services
- EC2 (Elastic Compute Cloud)
- RDS (MySQL)
- VPC (Virtual Private Cloud)
- Security Groups

### 💻 Tools & Technologies
- Linux (Amazon Linux)
- Apache Web Server
- PHP
- MySQL
- WordPress

---

## 🏗️ Architecture

- EC2 instance hosts the WordPress application
- Amazon RDS provides managed MySQL database
- VPC ensures secure networking
- Security Groups control access between EC2 and RDS

---

## ⚙️ Implementation Steps

1. Launched EC2 instance (Amazon Linux)
2. Installed Apache, PHP, and MySQL client
3. Downloaded and configured WordPress
4. Created RDS MySQL database
5. Configured Security Groups for secure access
6. Connected WordPress to RDS via wp-config.php
7. Deployed and tested the application

---

## 🔐 Security

- Database is not publicly accessible
- Access restricted via Security Groups
- Only EC2 instance can connect to RDS

---

## 🌐 Live Demo

http://3.235.126.121

---

## 📚 Key Learnings

- Deploying real-world cloud architecture
- Configuring EC2 and RDS integration
- Troubleshooting database connectivity
- Understanding AWS networking (VPC)

---

## 🚀 Future Improvements

- Add Load Balancer (ALB)
- Use Auto Scaling Group
- Implement HTTPS with SSL
- Use S3 for static content

---

## 👩‍💻 Author

Mariam Masood
