# Kubernetes Workshop

## Part 4

You will learn:

- What a `Namespace` is
- Filtering `kubectl` with namespace
- Adding a namespace to our `kubectl` context

### Follow Along Exercises

1. Create a namespace
2. Listing resources in a namespace `k8sw`
3. Updating `kubectl` context to `k8sw` namespace
4. Deploy a pod with explicit namespace
5. Deploy a pdo with implicit namespace

### Solo Exercises

1. Create a new `cli` namespace through `kubectl`
2. Create a new `manifest` namespace through manifest definition
3. Update `kubectl` context to `manifest` namespace
4. Switch `kubectl` context back to `default` namespace

### Command Help

#### Creating a Namespace with `kubectl`

```shell
kubectl create namespace namespace_name
```

#### Listing Resources within a Namespace

```shell
kubectl -n namespace_name get pods
```

#### Setting Explicit Namespace for Context

```shell
kubectl config set-context context_name --namespace namespace_name
```
