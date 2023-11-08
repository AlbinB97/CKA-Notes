# Imperative useful commands
This page shows most common and basic use cases, refer to the kubectl reference documentation for more in depth imperative commands.

https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands

### Creating a deployment
```
kubectl create deployment nginx --image nginx --replicas=3
```

### Scale a deployment
```
kubectl scale deployment nginx --replicas=4
```

### Creating a pod
```
kubectl run nginx-pod --image nginx
```

### Exposing a pod
```
kubectl expose pod nginx-pod --port 8080
```

### Creating these as YAML files to edit further
Simply add `--dry-run=client -o yaml > filename.yaml` to any imperative command
```
kubectl run nginx-pod --image nginx --dry-run=client -o yaml > nginx-pod.yaml
```
