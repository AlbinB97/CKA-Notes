# Crictl useful commands

Further reading: https://kubernetes.io/docs/tasks/debug/debug-cluster/crictl/

### List all containers
```
crictl ps -a
```

### Execute a command in a container
```
crictl exec -i -t <id> ls
```

### Container logs
```
crictl logs <id>
```
