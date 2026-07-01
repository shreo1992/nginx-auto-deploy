# 🚀 Project 4 – Automated Website Deployment with GitHub Actions

## 📖 Overview

This project demonstrates a complete **Continuous Deployment (CD)** pipeline using **GitHub Actions** and a **self-hosted runner** on a **CentOS 9** server running **Nginx**.

Whenever code is pushed to the `main` branch, GitHub Actions automatically deploys the latest version of the website to the web server without any manual intervention.

---

## 🎯 Objectives

- Automate website deployment using GitHub Actions.
- Configure a self-hosted GitHub Actions runner.
- Deploy a static website to an Nginx web server.
- Implement Continuous Deployment (CD).
- Gain hands-on experience with Linux administration and CI/CD automation.

---

## 🏗️ Architecture

```
                +----------------------+
                |   GitHub Repository  |
                +----------+-----------+
                           |
                     git push
                           |
                           ▼
              GitHub Actions Workflow
                           |
                           ▼
            Self-Hosted Runner (CentOS 9)
                           |
                           ▼
      Copy Website Files to Nginx Web Root
                           |
                           ▼
             Reload Nginx Automatically
                           |
                           ▼
                 Updated Website Live
```

---

## 📁 Project Structure

```
.
├── index.html
├── style.css
├── script.js
└── .github
    └── workflows
        └── deploy.yml
```

---

## ⚙️ Technologies Used

- GitHub Actions
- Git
- Linux
- CentOS 9
- Nginx
- Self-Hosted GitHub Runner
- SSH
- Bash

---

## 🚀 Features

- Automatic deployment on every push to the `main` branch.
- Self-hosted GitHub Actions runner.
- Automated website updates.
- Nginx integration.
- Secure deployment using Linux permissions.
- Passwordless sudo configuration for deployment tasks.

---

## 📋 Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions workflow starts.
3. Self-hosted runner executes the workflow.
4. Latest website files are copied to the Nginx document root.
5. Nginx reloads automatically.
6. Updated website becomes available immediately.

---

## 🖥️ Environment

| Component | Version |
|-----------|----------|
| Operating System | CentOS 9 |
| Web Server | Nginx |
| CI/CD | GitHub Actions |
| Runner | Self-Hosted |
| Version Control | Git |

---

## 🛠️ Challenges Faced

During the implementation, I encountered several real-world DevOps challenges:

- Configuring SSH authentication.
- Docker permission issues with the self-hosted runner.
- Passwordless sudo configuration.
- File permission management using ACLs.
- Troubleshooting deployment authentication.
- Nginx deployment verification.

Resolving these issues provided valuable experience in Linux system administration and CI/CD troubleshooting.

---

## 📷 Demo

### GitHub Actions Workflow





---

### Successful Deployment

<img width="1911" height="780" alt="image" src="https://github.com/user-attachments/assets/dc8591cd-8ac5-45df-b74b-869bfb05d539" />


---

### Website

<img width="1048" height="419" alt="image" src="https://github.com/user-attachments/assets/d2e897bd-bc11-48ab-8ead-3dc80f67921d" />


---

## 🎓 Skills Demonstrated

- Continuous Deployment (CD)
- GitHub Actions
- Self-Hosted Runners
- Linux Administration
- Nginx Administration
- CI/CD Pipelines
- Bash Scripting
- Git
- Troubleshooting
- Automation

---

## 🔮 Future Improvements

- Dockerize the application.
- Deploy using Docker Compose.
- Implement HTTPS with Let's Encrypt.
- Add automated testing.
- Add rollback capability.
- Deploy multiple environments (Development, Staging, Production).

---

## 👨‍💻 Author

**Shrief Elshorbagy**

Linux System Administrator | RHCSA | RHCE | DevOps Engineer

- GitHub: https://github.com/shreo1992
- LinkedIn: https://www.linkedin.com/in/shrief-elshorbagy-a33578b7/

---

## ⭐ If you like this project

Give this repository a ⭐ and feel free to fork it!
