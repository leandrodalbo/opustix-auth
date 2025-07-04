# Keycloak on Kubernetes

Deploys Keycloak to a Kubernetes cluster in the `event-auth` namespace.

## Requirements

- PostgreSQL running

## Deploy

```bash
kubectl apply -f namespace.yaml
kubectl apply -f keycloak-deployment.yaml
kubectl apply -f keycloak-service.yaml
```
