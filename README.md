## JVM Debugging an Application Running in Docker and Kubernetes With IntelliJ IDEA

### Create Docker Image
```
$ docker build -t restapi
```

#### Docker

```
$ docker run -d -p8080:8080 -p5005:5005 restapi:latest
```

#### Kubernetes

##### Apply deployment file

```
$ kubectl apply -f ./kubernetes/deployment.yaml
```

### Open port
open port using Intellij tool

### Reference
[Debugging an Application Running in Docker With IntelliJ IDEA By Baeldung](https://www.baeldung.com/docker-debug-app-with-intellij]) 