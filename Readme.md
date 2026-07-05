# 🚀 AWS EC2 Static Website Hosting

![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Linux](https://img.shields.io/badge/Linux-Amazon%20Linux-blue)
![Apache](https://img.shields.io/badge/Web%20Server-Apache-red)
![GitHub](https://img.shields.io/badge/GitHub-Project-black)

## 📌 Project Overview

This project demonstrates how to deploy a static website on an Amazon EC2 instance using Amazon Linux 2023 and Apache HTTP Server.

The objective of this project was to gain hands-on experience with AWS EC2, Linux administration, SSH connectivity, Apache Web Server, Git, and GitHub.

---

# 🏗️ Architecture

```
              Internet
                   │
                   ▼
          Security Group
      (SSH 22 | HTTP 80)
                   │
                   ▼
      Amazon EC2 Instance
      Amazon Linux 2023
                   │
                   ▼
        Apache HTTP Server
                   │
                   ▼
          Static HTML Website
                   │
                   ▼
             Web Browser
```

---

# ☁️ AWS Services Used

- Amazon EC2
- Security Groups
- Key Pair
- Amazon Linux 2023

---

# 🛠️ Technologies Used

- HTML5
- Apache HTTP Server
- Linux
- SSH
- Git
- GitHub

---

# 📋 Implementation Steps

- Launch Amazon EC2 Instance
- Configure Security Group
- Connect using SSH
- Update Linux Packages
- Install Apache HTTP Server
- Start and Enable Apache Service
- Deploy HTML Website
- Access Website using Public IP

---

# 💻 Commands Used

```bash
sudo dnf update -y

sudo dnf install httpd -y

sudo systemctl start httpd

sudo systemctl enable httpd

cd /var/www/html

sudo nano index.html
```

---

# 🎯 Skills Learned

- AWS EC2
- Linux Administration
- SSH Authentication
- Apache Web Server
- Security Groups
- Git
- GitHub

---

# 🚀 Future Improvements

- Responsive Website
- Custom Domain
- HTTPS using SSL
- Load Balancer
- Auto Scaling

---

# 👨‍💻 Author

**Ronak Pareek**

Cloud Computing | AWS | Linux | Git | DevOps