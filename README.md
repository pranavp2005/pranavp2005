
<!--
**pranavp2005/pranavp2005** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->



<!-- GitHub Profile README: Pranav Pateriya -->

<h1 align="center">Hi, I'm Pranav — Systems-minded Engineer (Cloud + Distributed Systems) who builds fast, resilient web experiences</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/pranav-pateriya/">LinkedIn</a> • 
  <a href="mailto:pranav@example.com">Email</a> • 
  <a href="https://docs.dremio.com/current/security/secrets-management/azure-key-vault/">Dremio AKV doc</a> • 
  <a href="#selected-projects">Projects</a> • 
  <a href="#talks--writing">Talks & Writing</a>
</p>

---

### What I do
- **Cloud & Distributed Systems**: Kubernetes-first designs, HA/DR, operators, secrets management, cross-cloud IAM, JWT-based license flows.
- **Frontend Performance**: React/Next.js, HLS streaming, CDN strategy, offline-first UX, Core Web Vitals.

### Operating Principles
- **Portability over lock-in** • **Simplicity under failure** • **Performance as a feature**.

---

## Selected Projects

### 1) Cloud-native PostgreSQL on Kubernetes (HA/DR, Backups) — *CloudNativePG operator*
**Why it matters**: Reliable, self-healing stateful workloads in k8s with automated failover and backups.  
**What I built**: Postgres clusters via CNPG, disaster recovery and scheduled backups; param’d manifests for dev/stage/prod; observability + runbooks.  
**Tech**: Kubernetes, CNPG operator, S3-compatible backups, Prometheus/Grafana.  
**Proof/Context**: CloudNativePG operator & docs.  
➡ Repo/Case study: `link` • Reference: [CNPG docs](https://cloudnative-pg.io/) | [GitHub](https://github.com/cloudnative-pg/cloudnative-pg)

---

### 2) License Agent & Subscription Orchestration (Multi-cloud)
**Why it matters**: Secure, auditable distribution of binaries/models across AWS/GCP with tenant scoping.  
**What I built**: JWT-based license validation; scoped S3/ECR read access; cross-account IAM policy writers; cert handling; cleanup on process termination; metrics.  
**Tech**: Go, AWS (S3/ECR/KMS/IAM), GCP (GCS/Artifact Registry), JWT, Terraform, Kubernetes.  
➡ Repo/Case study: `link`

---

### 3) Secrets Management for Analytics Platform (Azure Key Vault/Vault)
**Why it matters**: Removes plaintext secrets from configs; hardens enterprise deployments.  
**What I built**: Integrated AKV + Vault secret references into connector configs, standardized secret URI formats, authored runbooks.  
**Tech**: Azure Key Vault, HashiCorp Vault, AKS, Kubernetes, YAML tooling.  
**Proof**: Dremio docs that describe the integration:  
- Azure Key Vault (Enterprise): https://docs.dremio.com/current/security/secrets-management/azure-key-vault/  
- Secrets Management overview: https://docs.dremio.com/current/security/secrets-management/  
➡ Repo/Case study: `link`

---

### 4) Reels: HLS Streaming + CDN + Offline Caching (Perf-focused)
**Why it matters**: Sub-1.5s start times and smooth scrubbing on flaky networks.  
**What I built**: HLS player with intelligent preloading (N to N+4), ABR tuning, CloudFront caching, IndexedDB offline cache, Strapi CMS integration; perf budgets + RUM.  
**Tech**: React/Next.js, HLS.js, Service Workers, IndexedDB, CloudFront/S3, Strapi (REST/GraphQL).  
**Context**: CDN + Strapi best practices (public references).  
➡ Demo/Repo: `link` • Reading: https://strapi.io/blog/creating-a-video-streaming-app-with-strapi

---

### 5) LitePOS (Offline-first)
**Why it matters**: Transactional integrity without constant connectivity.  
**What I built**: <200 KB React app; write-ahead offline queue; conflict resolution; printable receipts; device-friendly UI.  
**Tech**: React 18, IndexedDB, Web Workers, Background Sync (fallback), PWA.

---

## Teaching & Mentorship
**TA — CSE 220 (Systems Fundamentals I), Stony Brook University**  
- Mentored in C, assembly, memory, computer architecture; labs/office hours; grading with clear rubrics; performance feedback loops.  
- Course overview for context: see CSE 220 description.  
Refs: https://www3.cs.stonybrook.edu/~ktm/courses/cse220/index.html

---

## Skills
**Cloud/DS**: Kubernetes, Operators (CNPG), AWS (S3/ECR/IAM/KMS), GCP (GCS/AR), AKS, Terraform  
**Security**: JWT, Secrets Mgmt (AKV, Vault), TLS/mTLS  
**Frontend**: React/Next.js, HLS.js, SW/IndexedDB, RUM, CWV  
**Langs**: Go, TypeScript, Python, Bash  
**Obs**: Prometheus, Grafana, Loki, OpenTelemetry

---

## Now / Next / Always
- **Now**: Researching multi-cloud failover playbooks; optimizing ABR heuristics for low bandwidth.  
- **Next**: K8s operators for app lifecycle; zero-downtime schema migrations.  
- **Always**: Measure → simplify → automate.

---

## Talks & Writing
- *“Secrets at Scale in Analytics Platforms”* — notes + examples (`link`)  
- *“Fast Starts on Slow Networks: Taming HLS”* — slides (`link`)  
- *“From Scripts to Operators: Day-2 Ops on K8s”* — blog (`link`)

---

## Let’s connect
- 💼 LinkedIn: https://www.linkedin.com/in/pranav-pateriya/  
- ✉️ Email: pranav@example.com

