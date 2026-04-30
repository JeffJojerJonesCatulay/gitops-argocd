# Local ArgoCD Demo

This directory contains a local demonstration project designed specifically for educational and demo purposes. 

## Overview

The project utilizes the standard `nginx` image to showcase a simple Kubernetes deployment managed through ArgoCD. It serves as a practical, easy-to-understand example of how GitOps principles are applied to deploy and manage an application.

## Components

- `deployment.yaml`: A basic Kubernetes Deployment manifest that spins up an `nginx:latest` container and exposes port 80.

## Screenshots

Below are screenshots capturing the ArgoCD application deployment, synchronization status, and resource tree:

### 1. Application Overview
![Application Overview](docs/images/Screenshot%202026-04-30%20181308.png)
*Description: Overview of the local-argo-demo application within the ArgoCD dashboard.*

### 2. Resource Tree and Sync Status
![Resource Tree and Sync Status](docs/images/Screenshot%202026-04-30%20181404.png)
*Description: Detailed view of the Kubernetes resources (Deployment, Pods, Services) managed by this GitOps repository.*

### 3. Application Details
![Application Details](docs/images/Screenshot%202026-04-30%20181426.png)
*Description: Synchronization details and health status of the deployed application.*

### 4. GitOps Sync Execution
![GitOps Sync Execution](docs/images/Screenshot%202026-04-30%20181518.png)
*Description: Visualizing the automated sync process pulling changes from the Git repository.*

### 5. Deployment Update
![Deployment Update](docs/images/Screenshot%202026-04-30%20181526.png)
*Description: ArgoCD recognizing and applying new changes (e.g., image version updates) to the cluster.*

### 6. Final Deployed State
![Final Deployed State](docs/images/Screenshot%202026-04-30%20181549.png)
*Description: The successful deployed state of the Nginx application in the local cluster.*
