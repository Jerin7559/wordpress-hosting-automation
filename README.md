# 🚀 Automated WordPress Hosting using Ansible (LEMP Stack on RHEL 9)

## 📌 Project Overview
This project demonstrates how to automate the deployment of a WordPress website using **Ansible** on a **LEMP stack (Linux, Nginx, MariaDB, PHP)** running on **Red Hat Enterprise Linux 9**.

The aim is to eliminate manual configuration and ensure **consistent, repeatable, and efficient deployment**.

---

## 🏗️ Architecture

User → Nginx → PHP-FPM → MariaDB  
           ↑  
        Ansible Automation  

---

## ⚙️ Technologies Used

- AWS EC2 – Hosting server  
- RHEL 9 – Operating system  
- Ansible – Automation tool  
- Nginx – Web server  
- PHP-FPM – Backend processing  
- MariaDB – Database  
- WordPress – CMS  
- phpMyAdmin – Database management  
- Let’s Encrypt – SSL (HTTPS)  
- SFTP – Secure file transfer  
- DuckDNS – Domain mapping  
- Git & GitHub – Version control  

---

## 🔧 Key Features

- Automated LEMP stack installation  
- WordPress deployment with database integration  
- User-based web hosting structure  
- HTTPS enabled using Let’s Encrypt  
- Secure file access using SFTP  
- Modular Ansible playbooks  
- Repeatable and scalable deployment  

---

## 📂 Project Structure
wordpress-hosting-automation/ │ ├── site.yml ├── ssl.yml ├── sftp.yml ├── inventory └── README.md

---

## 🚀 Workflow

### 1. Server Setup
- Launch EC2 instance  
- Configure security groups  
- Install RHEL 9  

### 2. Install LEMP Stack
- Install Nginx  
- Install PHP & PHP-FPM  
- Install MariaDB  

### 3. Ansible Automation
- Write playbooks  
- Configure services  
- Automate setup  

### 4. WordPress Deployment
- Download WordPress  
- Configure database  
- Setup virtual host  

### 5. Enable HTTPS
- Install Certbot  
- Generate SSL certificate  
- Configure HTTPS  

### 6. SFTP Setup
- Create user  
- Configure secure access  
- Restrict permissions  

---

## 🔐 Security

- HTTPS enabled using Let’s Encrypt  
- Secure SSH access  
- SFTP-based file transfer  
- Protected database credentials  

---

---

## 💡 Use Case

- Nginx → Handles HTTP/HTTPS requests  
- PHP-FPM → Executes backend logic  
- MariaDB → Stores application data  
- Ansible → Automates deployment  
- SSL → Secures communication  

---

## 🎯 Outcome

- Automated deployment pipeline  
- Reduced manual effort  
- Improved consistency  
- Real-world DevOps experience  

---

## 📚 Learning

- Ansible automation  
- Linux server management  
- Web server configuration  
- SSL and security setup  
- DevOps workflow  

---

## 🔗 Repository

https://github.com/Jerin7559/wordpress-hosting-automation  

---

## 🙌 Author

Jerin Joseph  
DevOps & Cloud Enthusiast  

---

