# PHP Application DevOps Pipeline on AWS

## 📌 Project Overview

This project demonstrates a fully automated DevOps pipeline for deploying a PHP web application on AWS using Terraform, Ansible, Jenkins, Docker.

The project focuses on infrastructure automation, CI/CD pipeline implementation, containerized deployment in a real cloud environment. Master, Test and Production Server are Used.

---

## 🚀 Tech Stack

### Cloud Platform
- AWS EC2

### DevOps Tools
- Terraform
- Ansible
- Jenkins
- Docker

### Application Stack
- PHP
- Apache
---

## ⚙️ Features

- Automated infrastructure provisioning using Terraform
- Dynamic inventory configuration with Ansible
- CI/CD pipeline automation using Jenkins
- Dockerized PHP application deployment using Ansible Playbook to Test and Production Server
- Fully automated cloud deployment workflow

---

## 🏗️ Architecture Flow

GitHub -> Jenkins(Master) -> Ansible -> Docker -> Test Server -> Manual_approval_after_testing -> Production Server

---

## 📂 Project Structure

```bash
terraform/
ansible/
website/
jenkins-pipeline
```

---

## 🐛 Problems Solved During Development

- Docker image compatibility issues
- Communication issue between Master to Test and Master to Production Server
- IP Address changed when EC2 Instances are started next day
---

## 📄 Detailed Documentation

See `Project_Report.pdf` for:
- Architecture diagrams
- Pipeline screenshots

---

## ✅ Final Outcome

Successfully built and deployed a fully automated DevOps pipeline for a PHP application on AWS with CI/CD, using Docker 
