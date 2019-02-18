# Kubernetes Workshop

## Part 7

You will learn:

- Introduction to `RBAC`
  - `Role`
  - `ServiceAccount`
  - `RoleBinding` and `ClusterRoleBinding`

### Follow Along Exercises

1. List all Roles
2. List all ServiceAccounts
3. List all RoleBindings
4. List all ClusterRoleBindings
5. In-Cluster `kubectl`:
   1. `kubectl run --rm -i --tty --restart=Never kubectl --image=bitnami/kubectl -- get pods`
   2. `kubectl run --rm -i --tty --restart=Never kubectl --image=bitnami/kubectl --command -- bash`

### Solo Exercises

1. Create a `Developer` role, in `default` namespace, with permissions:
   1. Pods in `default` namespace
2. Create a `PHPUK` service account in `default` namespace
3. Create PHPUKDeveloper role binding in `default` namespace
4. Create `kubectl` pod that uses this service account:
   1. Run `kubectl get pods` (This should work)
   2. Run `kubectl get pods -n kube-system` (This should fail)
