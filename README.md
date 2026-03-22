<h1 align="center">🚀 AWS Static Site CI/CD Pipeline</h1>

<p align="center">
A high-performance, cloud-native static hosting solution built with a modern DevOps mindset.
</p>

<p align="center">
<img src="https://img.shields.io/badge/AWS-S3-orange?style=for-the-badge&logo=amazonaws"/>
<img src="https://img.shields.io/badge/CDN-CloudFront-blue?style=for-the-badge&logo=amazonaws"/>
<img src="https://img.shields.io/badge/CI/CD-GitHub_Actions-black?style=for-the-badge&logo=githubactions"/>
<img src="https://img.shields.io/badge/Security-OIDC-green?style=for-the-badge"/>
</p>

---

## ⚡ Overview

Transforming a traditional static website into a **fully automated, globally distributed cloud application** using DevOps best practices.

✔ Zero manual deployment  
✔ Secure authentication (OIDC)  
✔ Global CDN delivery  
✔ Infrastructure as Code  

---

## 🏗️ Architecture & Workflow

```text
VS Code (Ubuntu)
      ↓
GitHub Repository
      ↓
GitHub Actions (CI/CD)
      ↓
Amazon S3 (Private Storage)
      ↓
CloudFront (CDN + HTTPS)
      ↓
Users Worldwide 🌍

```

## 🔁 CI/CD Pipeline Flow

🚀 Push code to main branch

⚙️ GitHub Actions automatically triggers

📦 Files synced to S3 bucket

🌐 CloudFront serves content globally

♻️ Cache invalidation ensures instant updates



## ✨ Features

🔥 Automated Deployment
No manual uploads — just git push

🔐 Security First
OIDC authentication (no exposed AWS keys)

⚡ High Performance
Delivered via CloudFront edge locations

📦 Infrastructure as Code
Deployment logic inside .github/workflows/deploy.yml


## 🛠️ Tech Stack


| Category    | Technology     |
| ----------- | -------------- |
| Hosting     | Amazon S3      |
| CDN         | CloudFront     |
| CI/CD       | GitHub Actions |
| Auth        | OIDC           |
| Environment | Ubuntu CLI     |

## 🚀 Deployment

git add .

git commit -m "Update: your changes"

git push origin main

That’s it. Pipeline handles everything automatically.

# 🌍 Live Demo

🔗 https://d340np7lnryc1p.cloudfront.net


## 📌 Project Highlights

✔ Fully automated DevOps pipeline

✔ Secure AWS integration without secrets

✔ Production-ready architecture

✔ Real-world cloud deployment

<h3 align="center">⚡ Built with 🧠 by Dhaval Chavda ⚡</h3> 
