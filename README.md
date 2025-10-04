# ⚙️ Ansible Nginx Automation Project

Automate the installation and configuration of **Nginx** using **Ansible**.  
This project demonstrates infrastructure automation by deploying a web server automatically.

![Ansible](https://img.shields.io/badge/Ansible-2.15+-black?logo=ansible)
![Nginx](https://img.shields.io/badge/Nginx-1.18+-green?logo=nginx)
![YAML](https://img.shields.io/badge/YAML-Configuration-blue)
![Platform](https://img.shields.io/badge/Platform-Linux-lightgrey)

---

## 📌 Project Goals

- 🧩 Automate the installation and configuration of **Nginx** using **Ansible**.  
- 📁 Deploy a custom HTML landing page to `/var/www/html/index.html`.  
- 🔁 Ensure the **Nginx** service starts automatically on boot.  
- 💻 Demonstrate how a single playbook can control multiple servers (simulated in demo).  
- 🧾 Provide clear **one-command** run steps and screenshots.

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|----------|
| 🐧 **Linux (Kali/Ubuntu)** | Environment |
| ⚙️ **Ansible** | Automation Engine |
| 🌐 **Nginx** | Web Server |
| 🧾 **YAML** | Playbook Syntax |
| 💡 **Markdown** | Documentation |

---
Demo Note:
This project is demonstrated on a local machine using Ansible’s localhost connection.
It simulates real server automation by running all tasks locally.
In an actual production setup, you can easily replace localhost with your real server IPs
inside the inventory.ini file to manage remote machines.

This approach is ideal for learning, testing, and showcasing Ansible automation workflows
without needing cloud or external servers.

