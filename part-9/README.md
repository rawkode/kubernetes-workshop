# Kubernetes Workshop

## Part 9

You will learn:

- Introduction to `Kustomize`

### Follow Along Exercises

1. Deploy `base`
2. Deploy `prod`

### Command Help

#### Generate Manifests with Kustomize

```shell
kustomize build ./directory
```

#### Apply Manifests with Kustomize

```shell
kustomize build ./directory | kubectl -f -
```
