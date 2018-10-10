# kubernetes-demo
在 Kubernetes 集群上部署 Java Web 或者 Spring Boot

----

## Build Project

```
$ mvn clean install
```

## Docker image

```
$ mvn dockerfile:build
```

## Kubernetes

```
$ kubectl create -f example-demo.yaml
```