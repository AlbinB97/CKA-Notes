### Show ports that a resource is listening to
```
netstat -npl | grep -i <resource>
```

### Show ports that a resource has established connection to
```
netstat -npa | grep -i <resource>
```

### Show IP interfaces
```
ip address
```

### Show IP interface that has the type bridge
```
ip address show type bridge
```

### List routes
```
ip routes
```