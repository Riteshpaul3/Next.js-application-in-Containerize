# Next.js Containerized Application with Kubernetes

This project demonstrates how to:
1. **Containerize a Next.js application** using Docker.
2. **Automate the build and push process** using GitHub Actions and GitHub Container Registry (GHCR).
3. **Deploy the containerized app to Kubernetes** using Minikube.

---

## 📋 Table of Contents

- [🚀 Local Setup](#-local-setup)
  - [Clone the Repository](#1-clone-the-repository)
  - [Install Dependencies](#2-install-dependencies)
  - [Build the Docker Image](#3-build-the-docker-image)
  - [Run the Application Locally](#4-run-the-application-locally)
- [🔧 GitHub Actions Workflow](#-github-actions-workflow)
  - [Overview](#overview)
  - [Workflow File](#workflow-file)
  - [Triggering the Workflow](#triggering-the-workflow)
- [⚙️ Kubernetes Deployment](#%EF%B8%8F-kubernetes-deployment)
  - [Setup Kubernetes (Minikube)](#setup-kubernetes-minikube)
  - [Kubernetes Manifests](#kubernetes-manifests)
  - [Deploy the Application](#deploy-the-application-to-kubernetes)
- [🛠 GitHub Container Registry (GHCR)](#-github-container-registry-ghcr)
- [📝 Notes](#%EF%B8%8F-notes)
- [📜 License](#license)

---

## 🚀 Local Setup

## 2. Install Dependencies

Install the required dependencies for the Next.js application:

npm install

## 3. Build the Docker Image

docker build -t nextjs-app .

## 4. Run the Application Locally

docker run -p 3000:3000 nextjs-app



## 5. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/Riteshpaul3/Next.js-application-in-Containerize.git
cd Next.js-application-in-Containerize

###
