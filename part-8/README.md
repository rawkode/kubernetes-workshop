# Kubernetes Workshop

## Part 8

You will learn:

- Introduction to `Helm`
- Introduction to `Helm Hub`

### Follow Along Exercises

1. Initialising Helm
2. Deploying MariaDB
3. Upgrading MariaDB
4. Deleting MariaDB
5. Purging MariaDB

### Solo Exercises

1. Deploy the following with Helm:
   1. Drone (Stable)
   2. CouchDB (Incubator)
   3. Contour (Rimusz)

### Command Help

#### Install `helm` into Cluster

```shell
helm init
```

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
