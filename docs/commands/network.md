# Networking useful commands

### Show IP interfaces
```
ip address
```
or
```
ip link
```

### Show IP interface that has the type bridge
```
ip address show type bridge
```

### List routes
```
ip routes
```

### Show ports that a resource is listening to
```
netstat -nplt | grep -i <resource>
```

### Show ports that a resource has established connection to
```
netstat -npat | grep -i <resource>
```
