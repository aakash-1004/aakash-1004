# Hi, I'm Aakash Rao 👋

**Cloud & Automation Engineer** at Zehntech Technologies, Indore

I build and deploy production-grade infrastructure using Docker, Kubernetes, Helm, Terraform, and AWS — with CI/CD pipelines via GitHub Actions and Jenkins, and GitOps workflows using ArgoCD.

---

## 🛠️ Tech Stack

**Cloud & IaC**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)

**Containers & Orchestration**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)

**CI/CD & GitOps**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)

**Security & Quality**
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat&logo=sonarqube&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat&logo=aquasecurity&logoColor=white)

**Monitoring**
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

**Languages & Tools**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 🚀 Featured Projects

| Project | Stack | Description |
|---------|-------|-------------|
| [boardgame-jenkins-cicd-pipeline](https://github.com/aakash-1004/boardgame-jenkins-cicd-pipeline) | Jenkins · Kubernetes (kubeadm) · SonarQube · Nexus · Trivy · Prometheus/Grafana | Self-managed K8s cluster with a Jenkins pipeline enforcing quality gates and RBAC-scoped deployment, plus full observability stack |
| [gitops-go-app](https://github.com/aakash-1004/gitops-go-app) | Go · Docker · Kubernetes · Helm · ArgoCD · GitHub Actions · cert-manager | GitOps pipeline on AWS EKS — automated CI (build, tag, push, sync), self-healing ArgoCD sync, topology-spread pod HA, automatic HTTPS via Let's Encrypt |
| [fullstack-chart](https://github.com/aakash-1004/fullstack-chart) | Helm · ArgoCD · Kubernetes | Helm chart + ArgoCD Application deployed via GitOps — deliberately keeps database credentials outside the automation entirely, provisioned once directly against the cluster rather than stored in Git, Helm values, or the ArgoCD manifest |
| [eks-irsa](https://github.com/aakash-1004/eks-irsa) | AWS EKS · IAM · OIDC · STS · Helm | IRSA trust chain for the AWS Load Balancer Controller — IAM OIDC provider, least-privilege role, ServiceAccount binding, verified by a controller pod provisioning a real ALB via STS AssumeRoleWithWebIdentity |
| [taskmanager](https://github.com/aakash-1004/taskmanager) | Flask · MongoDB · AWS EKS · Prometheus Operator | REST API deployed to EKS with persistent storage via the EBS CSI driver (IRSA-authenticated), Prometheus Operator + ServiceMonitor for metrics scraping, and a hardened WSGI deployment using Gunicorn |
| [flask-mongo-app](https://github.com/aakash-1004/flask-mongo-app) | Flask · MongoDB Atlas · Docker · GitHub Actions · EC2 | CI/CD pipeline with automated tests gating every deploy, and a secrets-handling fix — credentials are written to a permission-restricted file and referenced via Docker's `--env-file`, rather than exposed in a process's command-line arguments |

---

## 📜 Certifications

- ✅ Tutedude DevOps Course *(May 2026)*
- ✅ Coursera — Programming for Everybody (Python)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aakash-rao-b735b6244/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/aakash-1004)
