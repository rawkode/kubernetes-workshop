# Kubernetes Workshop

## Part 6

You will learn:

- What the `Ambassador` pattern is
- What the `Sidecar` pattern is
- What the `Adapter` pattern is

### Follow Along Exercises

1. Deploy `fpm` with nginx as an `Ambassador`
2. Deploy `nginx` with `git` as a `Sidecar`

### Solo Exercises

#### Adapter Pattern

Our `adapter` pod writes a random file to `/shared/output.txt` every 5 seconds

Add another container that will append this to a JSON document at `/shared/output.json`

**Example**

```json
# /shared/output.json
{"output": 45858}
{"output": 25}
{"output": 1378}
```

#### FaaS Over Web

If we have time, feel free to try our [FaaS Over Web](../part-x/faas-over-web/README.md) extra exercise.
