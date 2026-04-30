# GitOps ArgoCD

This repository is dedicated to GitOps practices specifically for ArgoCD deployments. It serves as the single source of truth for the desired state of Kubernetes clusters and applications managed via ArgoCD.

## Overview

By leveraging GitOps, all infrastructure and application deployment configurations are stored in this Git repository. ArgoCD continuously monitors this repository and automatically synchronizes the cluster state to match the configurations defined here.

## Usage

1. Connect this repository to your ArgoCD instance.
2. Create an ArgoCD Application or AppProject pointing to the desired manifests/charts within this repository.
3. Any changes merged into the tracking branch will be automatically synchronized and deployed by ArgoCD.
