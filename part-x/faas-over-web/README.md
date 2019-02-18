# Extras

## FaaS Over Web

Your challenge, should you choose to accept it, is to expose 3 FaaS (Functions as a Service).

1. functions/figlet
2. functions/sentimentanalysis
3. functions/markdown-render

### Help

You can do this many ways. I'll suggest two, but feel free to get creative.

#### Code Routing Deployment

Deploy each function as a `Deployment` with a `Service`.

Deploy your PHP application separately and route to each function based on a HTTP header to `$_GET` parameter.

#### Kubernetes Routing Deployment

Deploy each function with a PHP sidecar. Using `Ingress` rules, do path based routing to each PHP sidecar.
