# WIP Commands

This documentation is in the very early stages. So the structure of everything is not figured out yet. This page contains a bunch of commands that are useful, but don't belong on a page yet.

### Display information about a process
```
ps -aux | grep <process>
```

### Force delete a pod because exam environment is slow
```
kubectl delete pods <pod> --grace-period=0 --force
```