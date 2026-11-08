# bgm-shop-gitops

Kubernetes manifests synced by Argo CD for the bgm-shop GKE Autopilot cluster.

- `be/` — backend Deployment + Service
- `fe/` — frontend Deployment + Service
- `infra/` — namespace + LoadBalancers

Secrets (`bgm-shop-be-secrets`, keystore, etc.) stay in-cluster; they are not in this repo.
