# Python Flask + PostgreSQL Todo App on Azure using DevOps & Terraform

This project demonstrates end-to-end deployment of a **Python Flask + PostgreSQL** based Todo application on **Azure App Services**, orchestrated using **Azure DevOps Pipelines** and **Terraform** for infrastructure provisioning.

---

## Project Motivation

Manually provisioning infrastructure and deploying applications can be time-consuming and error-prone. This project aims to automate the entire workflow from infrastructure setup to application deployment using **Infrastructure as Code (IaC)** and **CI/CD pipelines**.

### Goals:
- Use Terraform to provision infrastructure on Azure.
- Automate infrastructure provisioning through Azure DevOps pipelines.
- Build and containerize a Flask application.
- Push the container image to **Azure Container Registry (ACR)**.
- Deploy the image from ACR to **Azure App Service for Containers**.
- Integrate PostgreSQL as the backend database.

---

## Tech Stack

| Category                | Technology                 |
|------------------------|----------------------------|
| App UI & Backend       | Python, Flask              |
| Database               | PostgreSQL (Azure DB)      |
| Containerization       | Docker                     |
| Infrastructure as Code | Terraform                  |
| CI/CD                  | Azure DevOps Pipelines     |
| Cloud Platform         | Microsoft Azure            |
| Deployment Service     | Azure App Service (Linux)  |
| Container Registry     | Azure Container Registry   |

---
