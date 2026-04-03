# Cosmin Pascariu — Cloud/DevOps Engineer

Mid-level DevOps engineer with ~4 years of experience building and operating Kubernetes-based platforms, both on bare-metal and in the cloud. I focus on infrastructure-as-code, GitOps workflows, and scalable CI/CD pipelines.

📍 Iași, România — open to remote

---

## Stack

**Kubernetes & Containers**

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Cilium](https://img.shields.io/badge/Cilium-F8C517?style=flat&logo=cilium&logoColor=black)

**Infrastructure as Code**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)

**CI/CD & GitOps**

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat&logo=aquasecurity&logoColor=white)

**Secrets & Security**

![Vault](https://img.shields.io/badge/HashiCorp_Vault-FFEC6E?style=flat&logo=vault&logoColor=black)
![cert-manager](https://img.shields.io/badge/cert--manager-003A9B?style=flat&logo=letsencrypt&logoColor=white)

**Observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Loki](https://img.shields.io/badge/Loki-F5A623?style=flat&logo=grafana&logoColor=white)

**Networking & DNS**

![PowerDNS](https://img.shields.io/badge/PowerDNS-003366?style=flat&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9?style=flat&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

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
| [pdns](https://github.com/pascariucosmin93/pdns) | Bare-metal PowerDNS setup — split-horizon DNS, local zones routed to authoritative, internet forwarded upstream |

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

## GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=pascariucosmin93&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pascariucosmin93&layout=compact&theme=dark&hide_border=true)

---

## Contact

**CV:** [cosmin-lab.com](https://cosmin-lab.com)
