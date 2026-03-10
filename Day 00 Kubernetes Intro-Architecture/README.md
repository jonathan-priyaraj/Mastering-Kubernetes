
![image](https://github.com/user-attachments/assets/4b8ab71c-429a-468b-baae-d4cd9f7334c2)

# Kubernetes Architecture

Welcome to the repository for our video on **Kubernetes Architecture** and **Container Orchestration**. In this video, we explore the essentials of Kubernetes and Docker Swarm, two popular tools for managing containerized applications.

## Overview

Container orchestration is crucial for managing large-scale container deployments. In this video, we cover the following topics:

- **Why Kubernetes?**
- **Kubernetes Architecture**

### Kubernetes

Kubernetes is a powerful tool for automating the deployment, scaling, and management of containerized applications. It offers features like:

- **TLS Secrets**
- **RBAC (Role-Based Access Control)**
- **Namespaces**
- **Stateful Sets**
- **Health Probes**
- **Environment Secrets**

## Example Architecture for multiple container located in different docker hosts

Our example setup includes three main components:

1. **Front End**
2. **Back End**
3. **Database**

![Screenshot 2024-07-23 122119](https://github.com/user-attachments/assets/4b328f19-51e5-4ed5-b365-8df33501e55a)

Each component runs on a Docker host with an Ubuntu operating system and uses Docker as the container engine. We demonstrate how both Kubernetes can manage these components effectively.

