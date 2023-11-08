### Creating a deployment
```
kubectl create deployment test-deployment --image nginx --replicas=3
```

### Creating a pod
```
kubectl run test-pod --image nginx
```

### Exposing a pod
```
kubectl expose pod test-pod --port 8080
```

### Creating these as YAML files to edit further
Simply add `--dry-run=client -o yaml > filename.yaml` to any imperative command
```
kubectl run test-pod --image nginx --dry-run=client -o yaml > nginx-pod.yaml
```
