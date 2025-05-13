# Node.js CI/CD Demo App 🚀

This is a simple Node.js web application used to demonstrate a basic **CI/CD pipeline** using **GitHub Actions** and **Docker**.

## 📌 Objective
Automate the steps to:
- Build the Node.js application
- Containerize it using Docker
- Push the image to DockerHub
- Trigger all these steps automatically on every push to `main`

## 🧰 Tools Used
- **GitHub Actions**
- **Node.js**
- **Docker & DockerHub**
- **GitHub**

## 📁 Project Structure

## ⚙️ GitHub Actions Workflow
The pipeline defined in `.github/workflows/main.yml` performs the following:

1. 🧪 Runs tests (if added)
2. 🛠️ Builds the Docker image
3. 📤 Pushes the image to DockerHub

## 🚀 How to Run Locally

```bash
docker build -t my-node-app .
docker run -p 3000:3000 my-node-app
https://chatgpt.com/c/68231034-54a0-800c-9245-56a4f844eae7#
