# Kubernetes Cluster Setup with Kind

## Overview
This project sets up a **Kubernetes cluster using Kind** and deploys various applications and services within the cluster. It includes:
- A **Kind cluster** with a control plane and worker nodes.
- Deployment of **Notes App** and **Nginx**.
- Various Kubernetes resources such as Deployments, Services, DaemonSet, Jobs, CronJobs, and Ingress.
- Port forwarding and namespace management.

---

## Prerequisites
Ensure you have the following installed on your system:
- **Docker** (Kind requires Docker to create the cluster)
- **Bash** (for running the setup script)

---

## Installation
To set up the cluster and deploy resources, run the following command:

```bash
bash setup.sh
