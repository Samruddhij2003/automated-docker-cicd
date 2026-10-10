# Automated Docker CI/CD Pipeline

A fully automated CI/CD pipeline built with Node.js, Docker, and GitHub Actions. Whenever changes are pushed to the main branch, GitHub Actions automatically runs unit tests, builds a Docker image, and pushes it to Docker Hub.

---

## 🛠 Tech Stack
- **Runtime:** Node.js
- **Containerization:** Docker
- **CI/CD:** GitHub Actions
- **Registry:** Docker Hub

---

## 🚀 How to Run Locally

Pull and run the container directly from Docker Hub:

```bash
docker pull demo124/devops-app:latest
docker run -d -p 3000:3000 --name devops-app demo124/devops-app:latest