# Extras

## FaaS Over Web

Your challenge, should you choose to accept it, is to expose 3 FaaS (Functions as a Service).

1. `functions/figlet`
2. `functions/sentimentanalysis`
3. `functions/markdown-render`

### Help

You can do this many ways. I'll suggest three, but feel free to get creative.

#### Code Based Routing

Deploy your own Service Router application that exposes a service and routes traffic to other services (proxy)

#### Kubernetes Ingress Routing

Deploy an Ingress controller to your cluster and leverage Kubernetes networking/v1 Ingress resources

- https://kubernetes.io/docs/concepts/services-networking/ingress/

#### Kubernetes Gateway API

Deploy a Gateway API controller to your cluster and leverage Kubernetes latest and greatest concepts for Kubernetes Ingress

- https://gateway-api.sigs.k8s.io/
