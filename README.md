# BeeAI Infra

A set of resources used to deploy hosted BeeAI Platform into Kubernetes cluster.

## Pre-requisites

- We operate within `beeai` namespace.
- Images are pulled from private github packages. Configure `ghcr-secret` secret, it will be used as `ImagePullSecret`.

## Deployment

- Apply `server.yaml` to deploy platform server as a service.
- Apply `web.yaml` to deploy patform website as a service.

## Ingress

Ingress shall be create to expose web service externally. It's definition is outside of the scope of this repo.