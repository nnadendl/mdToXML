You've made it this far! now that we have a Kubernetes cluster! we need a way to interact with it
the standard command line employed to communicate with it is [Kubectl](https://kubernetes.io/docs/tasks/tools/)


**In your terminal, let's try some commonly used `kubectl` commands!**

## Cluster Management
- Display endpoint information regarding the services and master in the cluster:

```bash
kubectl cluster-info
```
- Show the Kubernetes version functioning on the client and server:

```bash
kubectl version
```
- Get the configuration of the cluster:

```bash
kubectl config view
```
- Get a list of the available API resources:

```bash
kubectl api-resources
```
- List everything:

```bash
kubectl get all
```


## Namespaces
In Kubernetes, namespaces provide a mechanism for isolating groups of resources within a single cluster.

- Create a namespace:

```bash
kubectl create namespace my-first-ns
```
- Get a list of all namespaces:

```bash
kubectl get namespaces
```

- Show the detailed condition of one or more namespaces:

```bash
kubectl describe namespace my-first-ns
```

- Delete a namespace:

```bash
kubectl delete namespace my-first-ns
```

ℹ️ For a complete list of  `kubectl` commands and to learn more, check out this [Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/).

