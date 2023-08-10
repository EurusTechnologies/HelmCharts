# Generic Helm Chart

```console 
 Generic helm chart template that can be populated with specific configuration items to install multiple applications. You can use any image you want for the docker container used in the helm chart

1. one configurable helm chart for any type of applications
2. make kubernetes labels available for application as a configurable item in the helm charts
3. add configuration items (config_maps) in the helm chart for the deployed container
```

## Prerequisites
1. Kubernetes Cluster
2. Helm 
3. Docker Image for sample Application

## Versions
1. Kubernetes Cluster Version = 1.22
2. Helm Version = v3.10.0

## Running the helm chart for the Ist application
```console 
helm install app1 myapplication/ -f values/nginx.yaml
```

## Running the helm chart for the 2nd application
```console 
helm install app2 myapplication/ -f values/simpleweb.yaml
```

