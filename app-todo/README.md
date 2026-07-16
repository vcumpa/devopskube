# Exercise 1.2 - App Todo

This project creates a simple web server that prints  
**"Server started in port NNNN"** when started.

## Run with Docker
```bash
docker run vcumpa/app-todo:1.2
```

## Test with Kubernetes
```bash
kubectl apply -f manifests/deployment.yaml
kubectl get pods
kubectl logs <pod-name>
```