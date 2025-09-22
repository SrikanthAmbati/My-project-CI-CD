# My-project-CI/CD
Node.js CI/CD Pipeline with GitHub Actions & Docker

This project demonstrates **automated code deployment** using a **CI/CD pipeline** built with **GitHub Actions** and **DockerHub**.  
Whenever code is pushed to the `main` branch, the pipeline:

1. Installs dependencies & runs tests  
2. Builds a Docker image  
3. Pushes the image to **DockerHub**

---

## 📁 Project Structure
nodejs-ci-cd-demo/
│
├─ app.js # Sample Node.js server
├─ package.json # Dependencies & scripts
├─ Dockerfile # Docker image instructions
└─ .github/workflows/
└─ main.yml # GitHub Actions workflow

yaml
Copy code

---

## 🛠️ Tech Stack
- **Node.js** – Simple web server
- **GitHub Actions** – CI/CD pipeline
- **Docker & DockerHub** – Containerization & image registry

---

## ⚡ Prerequisites
- [Node.js 18+](https://nodejs.org/) & npm installed locally (for local testing)
- [Docker](https://www.docker.com/get-started) installed
- GitHub account & repository
- DockerHub account with a public repository

---

## ▶️ Local Setup & Run

Clone the repo and run locally:

```bash
git clone https://github.com/<your-username>/nodejs-ci-cd-demo.git
cd nodejs-ci-cd-demo
npm install
npm start
