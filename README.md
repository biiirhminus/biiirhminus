# Anton Novikov / Антон Новиков

**Senior DevOps Engineer** · Kubernetes and AWS EKS platforms

I design and run Kubernetes platforms: GitOps with ArgoCD and FluxCD, Terraform, CI/CD and observability. Right now I am responsible for an AWS/EKS reference architecture with 25+ clusters at Finstar Financial Group. 8 years in infrastructure.

**Senior DevOps-инженер** · платформы на Kubernetes и AWS EKS. 8 лет в инфраструктуре: Kubernetes, AWS EKS, Terraform, GitOps, CI/CD, мониторинг.

📍 Da Nang, Vietnam (UTC+7) · open to remote roles and relocation

- Website: [antonnovikov.com](https://antonnovikov.com/) · [на русском](https://antonnovikov.com/ru/)
- Resume: [English](https://cv.antonnovikov.com/resume) · [Русский](https://cv.antonnovikov.com/resume-ru)
- Weblog: [weblog.antonnovikov.com](https://weblog.antonnovikov.com/en/)
- LinkedIn: [linkedin.com/in/b-iii-rh-minus](https://linkedin.com/in/b-iii-rh-minus)
- Email: me@antonnovikov.com

**Stack:** Kubernetes · AWS EKS · Terraform · Ansible · FluxCD · ArgoCD · Helm · Kustomize · GitLab CI/CD · Prometheus · Grafana · VictoriaMetrics · OpenTelemetry · HashiCorp Vault

### Selected work

- **25+ AWS EKS clusters** in several regions, 100% Terraform and one shared Helm library chart, no manual work in the console. Karpenter consolidation keeps compute costs flat while the cluster count grows
- **FluxCD hub-and-spoke**: one hub reconciles 5 spoke clusters, 90%+ of manifests shared through a three-layer Kustomize setup. Ansible brings up a new cluster in under 30 minutes
- **24/7 airline GDS moved to containers**: 1500+ VMs on 500 hosts, XEN → Docker Swarm → Kubernetes, utilisation +40%, zero downtime
- **CI/CD from scratch** for Java, Python, PHP, .NET and C++: deploys went from hours to under 10 minutes, incidents from bad deploys −65%, MTTR 120 → 20 minutes
- **Startup infrastructure as the only DevOps engineer**: a new environment in 30 minutes instead of 3 days, RPO < 1 h and RTO < 30 min, zero data loss in 15 months

### Homelab

The sites above run on my own platform: two single-node k0s clusters (Prague and Russia) on Kubernetes 1.36.

- **Edge:** kgateway (Envoy, Gateway API), one HTTPS listener and a wildcard SAN certificate from cert-manager for ~40 subdomains
- **Observability:** VictoriaMetrics, VictoriaLogs, vmalert, blackbox probes; a deadman check runs from the second cluster
- **Ops:** 32 Ansible roles, nftables and SSH hardening, a private registry, SQLite replicated to S3 with Litestream, a test gate before every deploy

Write-ups: [APISIX → kgateway migration](https://weblog.antonnovikov.com/2026-11-13-apisix-to-kgateway-migration) and more in the [weblog](https://weblog.antonnovikov.com/en/).

### Latest posts

<!-- BLOG-POST-LIST:START -->
<!-- BLOG-POST-LIST:END -->

### Courses

The Linux Foundation, 2026:
[LFS158 Introduction to Kubernetes](https://www.credly.com/badges/b6587d89-087b-4a5d-a4fc-c5455eb6fd2d/public_url) ·
[LFS162 Introduction to DevOps and SRE](https://www.credly.com/badges/2472cbda-3a22-4f54-83e4-34bfe7b80546/public_url) ·
[LFS157 Introduction to Serverless on Kubernetes](https://www.credly.com/badges/3080a11f-d24b-4e54-9ad0-3a45cf5a04b3/public_url) ·
[LFS101 Introduction to Linux](https://www.credly.com/badges/a384e065-3039-4dce-8c7e-8111152fa637/public_url)
