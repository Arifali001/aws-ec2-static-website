# 🚀 AWS EC2 Static Website Hosting

A simple and practical cloud deployment project where a static website built using **HTML, CSS, and JavaScript** is hosted on an **AWS EC2 Ubuntu server** using the **Nginx web server**.

## 🌐 Project Overview

This project demonstrates how a static website can be deployed and hosted on the cloud using AWS EC2.

The website source code is maintained on **GitHub**, transferred to the EC2 server, and served to users through **Nginx**.

### 🔄 Deployment Flow

Local Website
   ↓
Git & GitHub
   ↓
AWS EC2 (Ubuntu)
   ↓
Nginx Web Server
   ↓
EC2 Public IP
   ↓
🌐 Live Website

## 🛠️ Technologies & Tools

- HTML5
- CSS3
- JavaScript
- Git
- GitHub
- AWS EC2
- Ubuntu Linux
- Nginx

## ☁️ AWS Services Used

### Amazon EC2
Used to create and run the cloud server where the website is hosted.

### Nginx
Used as the web server to serve the HTML, CSS, JavaScript, and other website files.

## ⚙️ Deployment Steps

1. Created a static website using HTML, CSS, and JavaScript.
2. Created a GitHub repository for version control.
3. Pushed the website source code to GitHub using Git.
4. Launched an Ubuntu EC2 instance on AWS.
5. Connected to the EC2 instance using SSH.
6. Installed Git and Nginx on the EC2 server.
7. Cloned the GitHub repository into the EC2 server.
8. Deployed the website files to the Nginx web directory.
9. Started and configured the Nginx web server.
10. Accessed the live website using the EC2 Public IPv4 address.

## 🔐 Security Configuration

The EC2 Security Group was configured to allow:

- SSH – Port 22
- HTTP – Port 80

## 📸 Project Preview

The website is successfully hosted on AWS EC2 and is accessible through the EC2 Public IP address.

## 🎯 Key Learning

Through this project, I learned:

- Basics of AWS EC2
- Linux server management
- SSH connection
- Nginx web server configuration
- Git and GitHub
- Website deployment
- Cloud-based web hosting
- AWS Security Groups and ports

## 🚀 Future Improvements

- Add a custom domain name
- Configure HTTPS using SSL/TLS
- Implement GitHub Actions CI/CD
- Add AWS monitoring using CloudWatch
- Configure automatic deployment

## 👨‍💻 Author

**Arif Ali**

B.Tech Computer Science Engineering

---

⭐ If you find this project useful, feel free to explore the repository.
