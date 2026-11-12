# eamghar-iot

Kubernetes manifests deployed by Argo CD for Inception-of-Things, Part 3.

`manifests/deployment.yaml` runs `wil42/playground` in the `dev` namespace.
Change the image tag (`v1` / `v2`) and push: Argo CD syncs the cluster.
