# Kubernetes Workshop

## Part 3

You will learn:

- What a `ConfigMap` is
- How to mount a config map as environment variables
- How to expose a config map as a file
- How to navigate the Kubernetes documentation 😂

### Follow Along Exercises

1. Creating `simple-config` config map
2. Creating `nginx-config` config map
3. Mounting whole config map as environment variables
4. Mounting whole config map as files

### Solo Exercises

1. Deploy `nginx` pod
2. Mount `nginx-config` to `/etc/nginx/nginx.conf`
3. Add `virtual-host.conf` to `nginx-config` config map
4. Mount virtual-host to `/etc/nginx/conf.d/my-web.conf`
5. Create a new `content` config map with `index.html`
6. Mount into `nginx` pod
7. Add / expose port `81` in `nginx` pod
8. Port forward to new virtual host

### Links

- [Kubernetes Documentation](https://kubernetes.io/docs/)
