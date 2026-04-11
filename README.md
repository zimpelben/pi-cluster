# pi-cluster
Kubernetes homelab

Self-hosted multi-node cluster running on raspberry pi's using k3s and FluxCD.

## Stack Overview

| Layer | Tool |
| --- | --- |
| Kubernetes | k3s |
| GitOps | FluxCD |
| Networking | Traefik |
| Monitoring | kube-pormethues-stack |
| App Packing | Helm, Kustomize |
| Database | CloudNative-PG |
| Automated dependency updates | Renovate |

## Host Specs

| Spec | Control plane | Worker node |
| --- | --- | --- |
| Machine | Raspberry Pi 4 | Raspberry Pi 4 |
| Memeory | 8 GB | 4 GB |
| Storage | 64 GB | 64 GB |

## Deployed Applications

| App | Function |
| --- | --- |
| Linkding | Bookmark manager |
| Audobookshelf | Audiobook and podcast server |
| Prometheus & Grafana | Monitoring & Dashboards |
| Mysql | Database |

## Next steps
- Add more apps to the cluster
- Build homelab dashboard
- Resolve CloudNative-PG port issues
