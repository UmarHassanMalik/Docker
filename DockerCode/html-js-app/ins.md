#  containerize this app



```
docker build -t first-docker-app .
```
```
docker container run --name=first-docker-cont -d -p 8500:80 first-docker-app

```

