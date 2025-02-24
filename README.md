# BeeAI Infra

A set of resources used to deploy hosted BeeAI Platform into Kubernetes cluster.

## Pre-requisites

- We operate whithin `beeai` namespace.
- Images are pulled from private github packages. Configure `ghcr-secret` secret, it will be used as `ImagePullSecret`.

## Resources

- Apply `server.yaml` to deploy platform server as a service.