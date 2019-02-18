# Part X

## "Production" WordPress Deployment

Your challenge, should you choose to accept it, is to deploy WordPress, with backing DB, to your Kubernetes cluster.

### Rules

- Use Helm to deploy your backing database
- Write a generic Helm chart for deploying web applications and use this for your WordPress `Deployment`
- WordPress configuration should be injected by ConfigMap, defined in our `values.yaml`
