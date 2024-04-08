# Kubernetes Workshop

## Part 8

You will learn:

- Introduction to `Helm`
- Introduction to `Helm Hub`

### Follow Along Exercises

1. Initialising Helm
2. Deploying PostgreSQL
3. Upgrading PostgreSQL
4. Deleting PostgreSQL
5. Purging PostgreSQL

### Solo Exercises

1. Deploy the following with Helm:
   1. Drone (Stable)
   2. CouchDB (Incubator)
   3. Contour (Rimusz)

### Bonus Exercises

1. Write your own Helm chart to deploy your own application
    1. If you don't have one, deploy `payloadcms`

### Command Help

#### Create, or Update, Helm Release

```shell
helm upgrade --install -f values.yaml release_name chart_repository/chart_name
```

#### Deleting a Helm Release

```shell
helm delete release_name
```

#### Purging a Helm Release

```shell
helm delete --purge release_name
```

#### Add New Repository

```shell
helm repo add repository_name repository_uri
```

#### Creating a New Chart

```shell
helm create
```
