Install Minikube
https://minikube.sigs.k8s.io/docs/start/

Minikube use docker desktop

```
minikube -p minikube docker-env --shell powershell | Invoke-Expression
```

Build Docker image in minikube

```
docker build -t image-name:v1
```

Install Helm

```
helm install <chart name> .
```

Check jobs

```
kubectl get jobs
```

Get pods
```
kubectl get pods
```

Check logs
```
kubectl logs <pod name>
```
