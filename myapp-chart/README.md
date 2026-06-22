# Reusable Helm Chart

Features
- Deployment
- Service
- ConfigMap
- Secret
- Ingress
- Horizontal Pod Autoscaler

Environments
- dev
- qa
- prod

Install:
helm install myapp . -f values-dev.yaml
helm install myapp . -f values-qa.yaml
helm install myapp . -f values-prod.yaml
