# Cosmin Pascariu — Cloud/DevOps Engineer

Mid-level DevOps engineer with ~4 years of experience building and operating Kubernetes-based platforms, both on bare-metal and in the cloud. I focus on infrastructure-as-code, GitOps workflows, and scalable CI/CD pipelines.

📍 Iași, România — open to remote

---

## Stack

**Kubernetes & Containers**
`Kubernetes` `Helm` `Argo CD` `Docker` `Gateway API` `Cilium` `BGP`

**Infrastructure as Code**
`Terraform` `Ansible` `Azure AKS` `AWS ECS` `Proxmox`

**CI/CD & GitOps**
`GitHub Actions` `GitOps` `Trivy` `GHCR`

**Secrets & Security**
`HashiCorp Vault` `External Secrets Operator` `Sealed Secrets` `cert-manager`

**Observability**
`Prometheus` `Grafana` `Loki` `Alloy`

**Storage & Networking**
`SeaweedFS` `S3-compatible storage` `HAProxy` `FRR` `BGP` `Cloudflare`

---

## Projects

### Homelab — Self-hosted Kubernetes (bare-metal, Proxmox)

| Repo | What it is |
|------|------------|
| [infrastructure-overview](https://github.com/pascariucosmin93/infrastructure-overview) | Architecture overview of the full homelab and cloud stack — Mermaid diagrams, component inventory |
| [argocd-apps](https://github.com/pascariucosmin93/argocd-apps) | App-of-apps GitOps repo — one `kubectl apply` bootstraps the entire cluster via sync waves |
| [secrets-management](https://github.com/pascariucosmin93/secrets-management) | Vault HA (Raft, 3 replicas) + ESO + Sealed Secrets + cert-manager — full GitOps secrets pipeline |
| [monitoring-stack](https://github.com/pascariucosmin93/monitoring-stack) | Prometheus + Grafana + Loki + Alloy deployed via Argo CD, with Grafana alerting to Discord |
| [dasboard-kube](https://github.com/pascariucosmin93/dasboard-kube) | Grafana dashboards as code — Cilium BGP Control Plane, Kubernetes Cluster Status, provisioned via Kustomize |
| [k8s-network-policies](https://github.com/pascariucosmin93/k8s-network-policies) | Cilium NetworkPolicies for the homelab cluster — includes fixes for kube-proxy-replacement mode |
| [vm-bootstrap-ansible](https://github.com/pascariucosmin93/vm-bootstrap-ansible) | Ansible roles for VM provisioning — common, bootstrap, hardening (SSH, fail2ban, sysctl, auditd) |
| [k8s-networking](https://github.com/pascariucosmin93/k8s-networking) | Bare-metal K8s networking — Cilium BGP, Gateway API, FRR, no MetalLB |
| [k8s-sh](https://github.com/pascariucosmin93/k8s-sh) | Shell scripts for bootstrapping and maintaining a bare-metal kubeadm cluster |

### Cloud — Azure & AWS

| Repo | What it is |
|------|------------|
| [azure-aks-platform](https://github.com/pascariucosmin93/azure-aks-platform) | Production-grade AKS landing zone — Terraform, hub-spoke network, ACR, Key Vault, TFLint + Checkov |
| [aws-infra](https://github.com/pascariucosmin93/aws-infra) | AWS ECS Fargate platform — Terraform modules for VPC, ALB, WAF, Cognito, Secrets Manager, per-env remote state |

### Applications

| Repo | What it is |
|------|------------|
| [calculatorgaz](https://github.com/pascariucosmin93/calculatorgaz) | Multi-service gas price platform — Next.js, PostgreSQL, OCR microservice, deployed on K8s via Argo CD |
| [gaz-gitops](https://github.com/pascariucosmin93/gaz-gitops) | GitOps manifests for the gaz platform — Helm charts, image tags auto-updated by CI |
| [s3-auto](https://github.com/pascariucosmin93/s3-auto) | Terraform automation for on-prem S3-compatible storage with SeaweedFS on Proxmox |
| [cv-website](https://github.com/pascariucosmin93/cv-website) | Personal CV site — Nginx, Docker, GHCR, deployed via Argo CD with Trivy scanning |

---

## Contact

**CV:** [cv.cosmin-lab.com](https://cv.cosmin-lab.com)
