# App Log Output

This application prints log messages with a UUID and timestamp.

## Run with Docker
```bash
docker run vcumpa/app-log-output:1.1
```

## Test with Kubernetes
```bash
kubectl apply -f manifests/deployment.yaml
kubectl get pods
kubectl logs <pod-name>
```