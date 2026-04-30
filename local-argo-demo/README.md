# Local ArgoCD Demo

This directory contains a local demonstration project designed specifically for educational and demo purposes. 

## Overview

The project utilizes the standard `nginx` image to showcase a simple Kubernetes deployment managed through ArgoCD. It serves as a practical, easy-to-understand example of how GitOps principles are applied to deploy and manage an application.

## Components

- `deployment.yaml`: A basic Kubernetes Deployment manifest that spins up an `nginx:latest` container and exposes port 80.

## Screenshots

Below are screenshots capturing the ArgoCD application deployment, synchronization status, and resource tree:

### 1. Git Commit Trigger
![Git Commit Trigger](docs/images/Screenshot%202026-04-30%20181308.png)
*Description: The Git commit pushing the updated code, which acts as the trigger for ArgoCD.*

### 2. Port Forwarding Argo Server
![Port Forwarding Argo Server](docs/images/Screenshot%202026-04-30%20181404.png)
*Description: Port forwarding the ArgoCD server service to access the UI locally.*

### 3. Running ArgoCD Pods
![Running ArgoCD Pods](docs/images/Screenshot%202026-04-30%20181426.png)
*Description: Verifying that all ArgoCD system pods are running correctly.*

### 4. ArgoCD Interface
![ArgoCD Interface](docs/images/Screenshot%202026-04-30%20181518.png)
*Description: The main ArgoCD web interface showing the application status.*

### 5. Deployment Update of the Pods
![Deployment Update of the Pods](docs/images/Screenshot%202026-04-30%20181526.png)
*Description: The application deployment updating the application pods in the cluster.*

### 6. Running Pod States
![Running Pod States](docs/images/Screenshot%202026-04-30%20181549.png)
*Description: The final state showing the application pods successfully running.*
