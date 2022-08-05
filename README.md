# learn-operator
how to start with k8s operator

# local kubernetes cluster
you can use [kind](https://kind.sigs.k8s.io/) to setup a local cluster.
config file are located in kind/config.yaml and run it with
```
kind create cluster --name local-cluster --config kind
```