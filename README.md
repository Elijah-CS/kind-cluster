# Kind Cluster

## Build Cluster
```
kind create cluster --config kind-config.yaml
```

## Add Ingress Support
```
kubectl apply -f config/deploy-ingress-nginx.yaml
```
