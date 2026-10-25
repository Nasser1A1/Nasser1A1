<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=18&pause=1200&color=00FF9C&background=0D0221&center=true&vCenter=true&width=700&height=70&lines=%3E+PLAYER+1%3A+MAHMOUD;%3E+CLASS%3A+DEVOPS+%2F+PLATFORM+ENGINEER;%3E+HOME+BASE%3A+KUBERNETES;%3E+PRESS+START+TO+SHIP" alt="Typing SVG" />
</a>

<br/>

![Level](https://img.shields.io/badge/LEVEL-25-FF00AA?style=for-the-badge&labelColor=0D0221)
![Class](https://img.shields.io/badge/CLASS-PLATFORM_ENGINEER-00FF9C?style=for-the-badge&labelColor=0D0221)
![Guild](https://img.shields.io/badge/GUILD-NAMSHI_%2F_NOON-FFD300?style=for-the-badge&labelColor=0D0221)
![Status](https://img.shields.io/badge/STATUS-SHIPPING-00E5FF?style=for-the-badge&labelColor=0D0221)

</div>

---

## 👾 `> whoami`

Senior infrastructure / platform engineer at **Namshi / noon**. I keep production Kubernetes clusters healthy, build the plumbing other engineers rely on, and increasingly point AI agents at the boring parts of engineering.

```text
> uptime ........ always chasing 99.99%
> favorite_bug .. the one that hid for six days behind a readiness probe
> weapon ........ kubectl, istioctl, and way too many gcloud flags
```

---

## 🕹️ Main Quests

### 📚 Autonomous Documentation Pipeline
Built an agent-driven pipeline that generates developer docs across **thousands of repositories**, unattended.
- Claude Agent SDK on Vertex AI, run as a Kubernetes CronJob
- GCS-backed work queue with bounded concurrency, backoff with jitter, and a shared circuit breaker
- Per-repo GitHub Actions workflows, Workload Identity Federation, least-privilege IAM
- Hardened pods (seccomp, dropped capabilities, read-only root filesystem) plus prompt-injection defenses
- Prompt caching and model-fallback strategy to cut cost per repo, with hard per-repo budget caps

### 🔎 Cross-Repo Knowledge & Search
Designed the architecture for querying the whole codebase like a single system.
- Dependency graph design (repo-level and module-level)
- RAG stack: tree-sitter AST chunking, code embeddings, Qdrant
- vLLM embedding service on multi-GPU Vertex AI custom jobs
- Chat agent over generated docs and GitHub code search

### ☸️ Production GKE Operations
- Rightsizing and troubleshooting a large production GKE cluster
- HPA / VPA coexistence, Node Auto-Provisioning, spot-pool memory pressure
- Istio / Envoy debugging: mTLS, VirtualServices, DestinationRules, access logs
- Incident response: scale-up feedback loops, `ImagePullBackOff`, node recovery over serial console
- Built an interactive cluster-topology dashboard across namespaces and the Istio mesh

### 🛠️ Side Missions
- Online schema change on a multi-million-row MySQL table with `pt-online-schema-change`
- GCP cost audits across production projects
- Temporal workflow failure alerting with Managed Prometheus and PromQL
- Branch protection and merge-strategy standards for frontend repos

---

## 🧰 Inventory

<div align="center">

![GCP](https://img.shields.io/badge/Google_Cloud-00FF9C?style=for-the-badge&logo=googlecloud&logoColor=black)
![GKE](https://img.shields.io/badge/GKE-00E5FF?style=for-the-badge&logo=kubernetes&logoColor=black)
![Istio](https://img.shields.io/badge/Istio-FF00AA?style=for-the-badge&logo=istio&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-FFD300?style=for-the-badge&logo=googlecloud&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-9D4EDD?style=for-the-badge&logo=githubactions&logoColor=white)

![BigQuery](https://img.shields.io/badge/BigQuery-00FF9C?style=for-the-badge&logo=googlebigquery&logoColor=black)
![Spanner](https://img.shields.io/badge/Cloud_Spanner-00E5FF?style=for-the-badge&logo=googlecloud&logoColor=black)
![Redis](https://img.shields.io/badge/Memorystore-FF00AA?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-FFD300?style=for-the-badge&logo=postgresql&logoColor=black)
![Prometheus](https://img.shields.io/badge/Prometheus-9D4EDD?style=for-the-badge&logo=prometheus&logoColor=white)

![Python](https://img.shields.io/badge/Python-00FF9C?style=for-the-badge&logo=python&logoColor=black)
![Temporal](https://img.shields.io/badge/Temporal-00E5FF?style=for-the-badge&logo=temporal&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FF00AA?style=for-the-badge&logo=linux&logoColor=white)

</div>

---

## 📊 Score Board

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Nasser1A1&show_icons=true&theme=radical&hide_border=true&bg_color=0D0221&title_color=00FF9C&icon_color=FF00AA&text_color=FFFFFF" height="165" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=Nasser1A1&theme=radical&hide_border=true&background=0D0221&ring=00FF9C&fire=FF00AA&currStreakLabel=00FF9C" height="165" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Nasser1A1&layout=compact&theme=radical&hide_border=true&bg_color=0D0221&title_color=00FF9C&text_color=FFFFFF" height="150" />

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Nasser1A1/Nasser1A1/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Nasser1A1/Nasser1A1/output/github-snake.svg" />
  <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/Nasser1A1/Nasser1A1/output/github-snake.svg" />
</picture>

</div>

---

## 🎯 Current Side Quests

- 🎓 Leveling up on Google Cloud (Associate Cloud Engineer, then maybe Professional Cloud Architect)
- 🧠 Giving AI agents persistent memory of repos and infra
- 💸 Making LLM-powered tooling cheaper and smarter per run

---

<div align="center">

```text
╔══════════════════════════════════╗
║   THANKS FOR VISITING. CONTINUE? ║
║         [ YES ]    [ YES ]       ║
╚══════════════════════════════════╝
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-00E5FF?style=for-the-badge&logo=linkedin&logoColor=black)](https://linkedin.com/in/YOUR_HANDLE)

</div>
