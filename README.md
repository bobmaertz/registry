# Docker Registry Helm Chart with Nginx and PVC

This Helm chart deploys a Docker registry with Nginx as a reverse proxy and a PersistentVolumeClaim (PVC) for persistent storage.

## Features
- Docker registry deployment
- Nginx reverse proxy
- Persistent storage using PVC

## Prerequisites
- Kubernetes cluster
- Helm 3.x

## Installation
```sh
helm install my-registry . --namespace <your-namespace> --create-namespace
```

## Configuration
You can override default values in `values.yaml` for custom configuration.

## Uninstallation
```sh
helm uninstall my-registry
```

## Notes
- Ensure your cluster supports PVCs.
- Update Nginx and registry configuration as needed in the chart templates.
