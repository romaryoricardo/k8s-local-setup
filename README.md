# K8S-LOCAL-SETUP

Configuration my enviroment to test

## Requirements

* Docker ✔️ 
* Kind ✔️ 
* Kubectl ✔️ 


### Creeate Kind Cluster

```bash
kind create cluster --name demo --config kind-config.yaml
```

### Deploy ingress controller

```bash
kubectl apply -f nginx-ingress-controller.yaml
```

### Deploy Metrcis Server

```bash
kubectl apply -f metrics-server.yaml
```