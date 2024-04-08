# Kubernetes Workshop

## Part 9

You will learn:

- Introduction to `Kustomize`

### Follow Along Exercises

1. Deploy `base`
2. Deploy `prod`

### Solo Exercises

1. Adopt Kustomize for your own application
	1. If you don't have one, deploy `payloadcms`

### Command Help

#### Generate Manifests with Kustomize

```shell
kustomize build ./directory
```

#### Apply Manifests with Kustomize

```shell
kustomize build ./directory | kubectl -f -
```
