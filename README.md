# Hi, I'm Ari Rahmat Romadhon 👋
### Cloud & DevOps Engineer | Infrastructure Automation, CI/CD, Containerization & Observability

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ari_Rahmat_Romadhon-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-arighmt67--bit-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/arighmt67-bit)
[![Email](https://img.shields.io/badge/Email-arirahmatromadhon%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arirahmatromadhon@gmail.com)

---

## 🎯 Production Engineering Portfolios & Automated Workflows

All repositories below are strictly production-grade: complete with automated GitHub Actions CI/CD workflows, automated testing matrices, security linting, and public live deployments or container images.

| Project / Monorepo | Core Tech Stack | Automation & Quality Gates | Live Artifact / URL |
| :--- | :--- | :--- | :--- |
| [**devops-engineer**](https://github.com/arighmt67-bit/devops-engineer) | Terraform, Kubernetes, Docker, Prometheus, Grafana | [![CI](https://github.com/arighmt67-bit/devops-engineer/actions/workflows/infra-lint.yml/badge.svg)](https://github.com/arighmt67-bit/devops-engineer/actions) | `kubeconform`, `terraform fmt/validate`, container smoke test |
| [**forum-api**](https://github.com/arighmt67-bit/forum-api) | Node.js, Hapi, PostgreSQL, Docker, AWS (EC2/EIP/EBS) | [![CI](https://github.com/arighmt67-bit/forum-api/actions/workflows/ci.yml/badge.svg)](https://github.com/arighmt67-bit/forum-api/actions) | [`ghcr.io/arighmt67-bit/forum-api:1.0.0`](https://github.com/arighmt67-bit/forum-api/pkgs/container/forum-api) |
| [**back-end-engineering**](https://github.com/arighmt67-bit/back-end-engineering) | Node.js, Python (pytest), Rust (cargo) | [![CI](https://github.com/arighmt67-bit/back-end-engineering/actions/workflows/ci.yml/badge.svg)](https://github.com/arighmt67-bit/back-end-engineering/actions) | Multi-language matrix tests (100% green) |
| [**front-end-engineer**](https://github.com/arighmt67-bit/front-end-engineer) | React 18, Vite, Lit, Webpack, TensorFlow.js | [![CI & Deploy](https://github.com/arighmt67-bit/front-end-engineer/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/arighmt67-bit/front-end-engineer/actions) | [arighmt67-bit.github.io/front-end-engineer](https://arighmt67-bit.github.io/front-end-engineer/) |

---

## 🛠️ Technical Competency & Tooling

```text
Cloud Providers      : AWS (EC2, VPC, EIP, EBS, S3, IAM), GCP (GKE, Cloud SQL, Compute MIG)
Infrastructure/IaC   : Terraform, Kubernetes (K8s), Docker, Docker Compose, GHCR
CI/CD & Automation   : GitHub Actions, Jenkins, Bash scripting, Python automation
Observability/SRE    : Prometheus, Grafana, Alerting, Health Checks (Liveness/Readiness)
Networking & Security: NGINX Reverse Proxy, Let's Encrypt TLS/SSL, DNS, UFW, Security Groups
Databases            : PostgreSQL, Redis
Programming/Scripting: Bash, Python, JavaScript/Node.js, Rust
```

---

## 📊 Automated End-to-End DevOps Architecture

```text
+-----------------------+      +-------------------------+      +---------------------------+
| Source Code & Config  | ---> | GitHub Actions CI/CD    | ---> | OCI Registry (GHCR)       |
| - Node.js / Python    |      | - Matrix Lint & Tests   |      | ghcr.io/arighmt67-bit/    |
| - Terraform HCL       |      | - ShellCheck & TFLint   |      | forum-api:1.0.0           |
| - K8s Manifests       |      | - Kubeconform Validator |      +---------------------------+
+-----------------------+      +-------------------------+                    |
                                                                              v
+-----------------------+      +-------------------------+      +---------------------------+
| Observability & SRE   | <--- | Kubernetes / Docker     | <--- | Automated Smoke Test      |
| - Prometheus Scrape   |      | - Liveness & Readiness  |      | - Container DB Connection |
| - Grafana Dashboards  |      | - Resource Limits (OOM) |      | - HTTP 200 OK Health Check|
+-----------------------+      +-------------------------+      +---------------------------+
```

---

## 📈 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=arighmt67-bit&show_icons=true&theme=tokyonight" alt="Ari's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arighmt67-bit&layout=compact&theme=tokyonight" alt="Top Languages" />
</p>
