# ArgoCD
# Kubernetes Manifests for ArgoCD Demo

This directory contains Kubernetes resource files used for deploying a sample app.

## Files

- `deployment.yaml`: Defines a Deployment with Nginx container.
- `service.yaml`: Exposes the deployment via NodePort Service.

## Apply Manually

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
