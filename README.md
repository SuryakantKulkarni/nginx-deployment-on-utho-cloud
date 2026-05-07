<div align="center">
  
# 🚀 NGINX Web Server Deployment on Utho Cloud

</div>

---

<div align="center">

[![Platform](https://img.shields.io/badge/Platform-Utho%20Cloud-blue?style=for-the-badge)]()
[![Web Server](https://img.shields.io/badge/Web%20Server-NGINX-brightgreen?style=for-the-badge&logo=nginx)]()
[![OS](https://img.shields.io/badge/OS-Ubuntu%2024.04-orange?style=for-the-badge&logo=ubuntu)]()
[![Cloud](https://img.shields.io/badge/Cloud-India%20Based%20Cloud-0A66C2?style=for-the-badge)]()

> **"Hands-on implementation is the best way to understand cloud and DevOps concepts."**

</div>

---

## Project Overview

This project demonstrates the deployment and configuration of an NGINX web server on **Utho Cloud**, an India-based cloud infrastructure platform.

The implementation includes:
- Provisioning an Ubuntu virtual machine
- Configuring security group rules
- Connecting securely via SSH
- Installing and managing NGINX
- Verifying deployment using the public IP address

---

## About Utho Cloud
Utho Cloud is an Indian cloud service provider that offers scalable and cost-effective cloud infrastructure solutions including virtual machines, networking, storage, and security services for developers and businesses.

---

## Technologies Used

| Cloud | OS | Web Server | Access |
|:---:|:---:|:---:|:---:|
| Utho Cloud | Ubuntu 24.04 | NGINX | SSH |

---

## Project Architecture

```text
User Browser
      ↓
Public IP
      ↓
Utho Cloud VM (Ubuntu)
      ↓
NGINX Web Server
```

---

## Step-By-Step Implementation 

### 1️⃣ Launch Cloud Instance
- Created Ubuntu VM on Utho Cloud
- Selected compute and storage configuration

### 2️⃣ Configure Security Groups
Allowed inbound traffic for:
- Port 22 (SSH)
- Port 80 (HTTP)

### 3️⃣ Connect via SSH

```bash
ssh root@<public-ip>
```

### 4️⃣ Install NGINX

```bash
sudo apt update
sudo apt install nginx -y
```

### 5️⃣ Verify NGINX Status

```bash
sudo systemctl status nginx
```

### 6️⃣ Verify Deployment
Accessed the application using the public IP in the browser.

---

## Screenshots

Project screenshots are available inside the `screenshots/` directory.

---

## Documentation

Detailed project documentation is available inside the `docs/` folder.

---

## Project Outcome

This project helped in understanding:
- Cloud instance provisioning
- Security group management
- Linux server administration
- Web server deployment workflow

The successful deployment of the NGINX welcome page confirmed that the server was properly configured and accessible over the internet.

---

<div align="center">

### 🚀 Keep Learning • Keep Building • Keep Exploring

</div>
