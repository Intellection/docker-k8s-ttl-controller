# docker-k8s-ttl-controller

[![release](https://github.com/Intellection/docker-k8s-ttl-controller/actions/workflows/release.yml/badge.svg)](https://github.com/Intellection/docker-k8s-ttl-controller/actions/workflows/release.yml) [![test](https://github.com/Intellection/docker-k8s-ttl-controller/actions/workflows/test.yml/badge.svg)](https://github.com/Intellection/docker-k8s-ttl-controller/actions/workflows/test.yml)

Docker image for [`TwiN/k8s-ttl-controller`](https://github.com/TwiN/k8s-ttl-controller), a Kubernetes controller that enables timed resource deletion using TTL annotation.

## Motivations

### How does this differ from upstream?

The current Docker image doesn't support ARM and we needed one that does. And [the review to add support](https://github.com/TwiN/k8s-ttl-controller/pull/95) took longer than we could wait.

## Usage

```
docker run --name k8s-ttl-controller zappi/k8s-ttl-controller:latest
```

For more detailed usage documentation [see upstream](https://github.com/TwiN/k8s-ttl-controller).
