# Helm chart postgres-demo

Ce chart déploie un serveur PostgreSQL dans Kubernetes avec initialisation d'une table `personnes` et insertion de données fictives.

## Prérequis

- Kubernetes 1.16+
- Helm 3+
- Argo CD (optionnel pour GitOps)

## Installation en local avec Helm

```bash
helm install postgres-demo ./postgres-demo
