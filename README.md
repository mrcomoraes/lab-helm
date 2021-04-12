# HELM - My stateless app

This Helm chart deploys a single nginx web server with HPA, readness and liveness probes configured.

This Helm chart is useful for testing connections and lab.

## Dependencies

Before starting, ensure that you have Helm and Kubectl binaries:

```bash
which helm
helm version
which kubectl
kubectl version --client
```

## How to use

After clone this repo, run:

```bash
cd helm
helm install my-stateless-app my-stateless-app --values my-stateless-app/values.yam
```

This commands deploys and running a nginx web server.

Feel free to modify!
