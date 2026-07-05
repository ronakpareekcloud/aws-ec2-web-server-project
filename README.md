# 🚀 AWS EC2 Static Website Hosting

<p align="center">

![AWS](https://img.shields.io/badge/AWS-EC2-orange?style=for-the-badge&logo=amazonaws)
![Amazon Linux](https://img.shields.io/badge/Linux-Amazon%20Linux%202023-yellow?style=for-the-badge&logo=linux)
![Apache](https://img.shields.io/badge/Apache-HTTP_Server-D22128?style=for-the-badge&logo=apache)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)
![HTML5](https://img.shields.io/badge/HTML5-Static_Website-E34F26?style=for-the-badge&logo=html5)

</p>

---

# 📖 Project Overview

This project demonstrates the deployment of a static HTML website on **Amazon EC2** using **Amazon Linux 2023** and **Apache HTTP Server**.

This project helped me gain hands-on experience with:

- Amazon EC2
- Security Groups
- SSH Connectivity
- Linux Administration
- Apache HTTP Server
- Git & GitHub
- Website Deployment

---

# ✨ Features

- ✅ Launch Amazon EC2 Instance
- ✅ Configure Security Groups
- ✅ Secure SSH Login
- ✅ Install Apache HTTP Server
- ✅ Deploy Static HTML Website
- ✅ Git Version Control
- ✅ GitHub Repository

---

# 🛠️ Technologies Used

- Amazon EC2
- Amazon Linux 2023
- Apache HTTP Server
- HTML5
- Linux
- Git
- GitHub
- SSH

---

# 🏗️ Architecture

```text
               User
                 │
           Web Browser
                 │
          Public IPv4 Address
                 │
        Amazon EC2 (t3.micro)
        Amazon Linux 2023
                 │
        Apache HTTP Server
                 │
         /var/www/html
                 │
            index.html
```

---

# 📂 Project Structure

```text
aws-ec2-web-server-project
│
├── index.html
├── README.md
└── screenshots
    ├── ec2-dashboard.png
    ├── launch-instance.png
    ├── key-pair.png
    ├── security-group.png
    ├── ec2-running.png
    ├── ssh-connect.png
    ├── ssh-login.png
    ├── system-update.png
    ├── apache-running.png
    ├── website-output.png
    └── github-repository.png
```

---

# ⚙️ Deployment Steps

### 1️⃣ Launch EC2 Instance

- Amazon Linux 2023
- t3.micro
- Create or Select Key Pair

---

### 2️⃣ Configure Security Group

Allow:

- SSH (Port 22)
- HTTP (Port 80)

---

### 3️⃣ Connect Using SSH

```bash
ssh -i "ronak-key.pem" ec2-user@Public-IP
```

---

### 4️⃣ Update System

```bash
sudo dnf update -y
```

---

### 5️⃣ Install Apache

```bash
sudo dnf install httpd -y
```

---

### 6️⃣ Enable Apache

```bash
sudo systemctl start httpd
sudo systemctl enable httpd
```

---

### 7️⃣ Deploy Website

```bash
sudo cp index.html /var/www/html/
```

---

# 💻 Commands Used

```bash
sudo dnf update -y
sudo dnf install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
sudo systemctl status httpd
sudo cp index.html /var/www/html/
```

---

# 📸 Project Screenshots

## AWS EC2 Dashboard

![](screenshots/ec2-dashboard.png)

---

## Launch EC2 Instance

![](screenshots/launch-instance.png)

---

## Configure Key Pair

![](screenshots/key-pair.png)

---

## Configure Security Group

![](screenshots/security-group.png)

---

## EC2 Instance Running

![](screenshots/ec2-running.png)

---

## SSH Connection

![](screenshots/ssh-connect.png)

---

## SSH Login

![](screenshots/ssh-login.png)

---

## System Update

![](screenshots/system-update.png)

---

## Apache HTTP Server Running

![](screenshots/apache-running.png)

---

## Live Website

![](screenshots/website-output.png)

---

## GitHub Repository

![](screenshots/github-repository.png)

---

# 🎯 Skills Demonstrated

- Amazon EC2
- Linux Administration
- Apache HTTP Server
- SSH
- Git
- GitHub
- Static Website Hosting
- Website Deployment

---

# 📚 Learning Outcomes

Through this project, I learned how to:

- Launch and configure an Amazon EC2 instance.
- Configure Security Groups for secure access.
- Connect securely using SSH.
- Install and manage Apache HTTP Server.
- Deploy a static website.
- Use Git and GitHub for version control.

---

# 🚀 Future Improvements

- HTTPS using SSL
- Custom Domain (Route 53)
- Load Balancer
- Auto Scaling
- CI/CD Pipeline
- Docker Deployment

---

# 👨‍💻 Author

**Ronak Pareek**

Cloud Computing | AWS | Linux | DevOps

📧 Email: ronakpareekcloud@gmail.com

🌐 GitHub: https://github.com/ronakpareekcloud

---

⭐ **If you found this project helpful, please consider giving it a Star!**