# Kubernetes Workshop

## Part 1

You will learn:

- What a `Pod` is
- How to create, update, and delete a pod
- Exporting a pod to `JSON` and `YAML`
- Port Forward traffic locally to your pod

### Follow Along Exercises

1. The anatomy of a Kubernetes manifest
2. Introduction to `kubectl`
3. Deploying the `sleep` pod

### Solo Exercises

1. Deploy a `nginx` image as a pod named `nginx`
2. Export `nginx` pod manifest as `JSON` and `YAML`
3. Port Forward to your `nginx` pod
4. Delete the `nginx` pod

### Command Help

#### Create a Resource from a Manifest

```shell
kubectl create -f manifest.yaml
```

#### Delete a Resource from a Manifest

```shell
kubectl delete -f manifest.yaml
```

#### Create or Update a Resource from a Manifest

```shell
kubectl apply -f manifest.yaml
```

#### Delete a Resource

```shell
kubectl delete resource_type resource_name
```

#### Exporting a Resource as Manifest

```shell
kubectl get resource_type resource_name -o format --export
```

#### Port Forward `localhost` to a Pod

```shell
kubectl port-forward pod_name local_port:container_port
```
