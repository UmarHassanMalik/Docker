#  containerize this app



```
docker build -t node-app-image .
```
```
docker container run --name=first-node-cont -d -p 8550:8080 node-app-image
```

