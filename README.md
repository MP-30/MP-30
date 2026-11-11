<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=230&section=header&color=0%3A991B1B%2C50%3AB4472F%2C100%3AD9775C&fontColor=FFFFFF&descColor=FDE2DA&text=Aditya%20Bhadauriya&fontSize=50&fontAlignY=35&desc=Python%20AI%20%26%20Backend%20Engineer%20%7C%20RAG%20%7C%20Platform%20Engineering&descSize=18&descAlignY=55&animation=fadeIn"/>
    <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=230&section=header&color=0%3A7F1D1D%2C50%3A9B2C2C%2C100%3AB4472F&fontColor=FFFFFF&descColor=FFFFFF&text=Aditya%20Bhadauriya&fontSize=50&fontAlignY=35&desc=Python%20AI%20%26%20Backend%20Engineer%20%7C%20RAG%20%7C%20Platform%20Engineering&descSize=18&descAlignY=55&animation=fadeIn" alt="Aditya Bhadauriya — Python AI & Backend Engineer | RAG | Platform Engineering"/>
  </picture>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=C8553D&center=true&vCenter=true&width=700&lines=Building+and+evaluating+production+RAG+systems;Agents+%C2%B7+MCP+%C2%B7+AWS+Bedrock+%C2%B7+pgvector;FastAPI+%C2%B7+Django+%C2%B7+Terraform+%C2%B7+CI%2FCD;Shipping+reliable+cloud-native+infrastructure" alt="Building and evaluating production RAG systems"/>
</p>

<p align="center">
  <a href="https://adityalive.tech/"><img src="https://img.shields.io/badge/🌐_Portfolio-9B2C2C?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/aditya-bhadauriya-99bb8a86/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:adityabhadauriya93@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://adityalive.tech/assets/resume.pdf"><img src="https://img.shields.io/badge/📄_Resume-7F1D1D?style=for-the-badge" alt="Resume"/></a>
  <img src="https://komarev.com/ghpvc/?username=MP-30&label=Profile%20Views&color=7F1D1D&style=for-the-badge" alt="Profile views"/>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F1D1D,100:C8553D" alt=""/>

## About Me

I'm **Aditya Bhadauriya**, a Python AI and backend engineer who builds, evaluates and deploys LLM systems. I've shipped RAG and agent services on **AWS Bedrock** for a healthcare document assistant, a banking GRC platform and a live multi-tenant RAG platform, the last with an evaluation suite that gates its CI. I have **4 years** of experience building FastAPI and Django services for fintech and enterprise clients, including the deployment and monitoring side. I moved into software from an electrical engineering career.

```yaml
apiVersion: engineer/v1
kind: Profile
metadata:
  name: aditya-bhadauriya
  labels:
    role: python-ai-backend-engineer
    focus: rag-agents-platform
spec:
  experience: "4 years"
  expertise:
    - RAG, hybrid retrieval & RAGAS evals
    - Agents & MCP (AWS Strands, Pydantic AI)
    - AWS Bedrock, pgvector, PostgreSQL
    - FastAPI, Django, Celery, async pipelines
    - AWS (ECS Fargate, EKS, Lambda, SQS/SNS, S3, IAM)
    - Infrastructure as Code (Terraform)
    - CI/CD (GitHub Actions + OIDC, Jenkins)
    - Observability (Datadog, OpenTelemetry, Prometheus, Grafana)
  learning:
    - Multi-agent orchestration (A2A)
    - LLM observability
    - Distributed Systems
  building: Academic Intelligence Platform (RAG + MCP on AWS)
```

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F1D1D,100:C8553D" alt=""/>

## Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/MP-30/Academic-Intelligence-Platform">Academic Intelligence Platform</a></h3>
      <p>Live multi-tenant RAG platform answering over CBSE curriculum PDFs with page-level citations. Hybrid retrieval (pgvector + full-text, fused with RRF), an AWS Strands agent that routes between private documents and live web search, and tools exposed as MCP servers in sidecar containers.</p>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat-square&logo=amazonaws&logoColor=white" alt="AWS Bedrock"/>
      <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector"/>
      <img src="https://img.shields.io/badge/MCP-000000?style=flat-square" alt="MCP"/>
      <img src="https://img.shields.io/badge/RAGAS-6366F1?style=flat-square" alt="RAGAS"/>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/MP-30/academic-intelligence-platform-terraform">Academic Intelligence Platform: Terraform</a></h3>
      <p>Infrastructure-as-code for the platform: VPC, private RDS, ECS Fargate, ALB and Cognito. Paired with GitHub Actions OIDC deploys, so there are no stored AWS credentials. Runs at about $48/month.</p>
      <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
      <img src="https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white" alt="ECS Fargate"/>
      <img src="https://img.shields.io/badge/Cognito-DD344C?style=flat-square&logo=amazonaws&logoColor=white" alt="Cognito"/>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/MP-30/AI-assisted-Linux-debugging">AI-assisted Linux Debugging</a></h3>
      <p>FastAPI service and CLI that snapshots a Linux host's health and uses runbook retrieval with a local LLM to suggest root causes and fixes.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square" alt="ChromaDB"/>
      <img src="https://img.shields.io/badge/RAG-6366F1?style=flat-square" alt="RAG"/>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/MP-30/hyper-scale-ops">Hyper Scale Ops</a></h3>
      <p>End-to-end Python application, containerized and shipped through Jenkins and GitHub Actions to Kubernetes with Datadog monitoring.</p>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm"/>
      <img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square" alt="AWS"/>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/MP-30/hyper-scale-ops-k8s">Hyper Scale Ops Helm Charts</a></h3>
      <p>Helm chart repository used to deploy Hyper Scale Ops onto Kubernetes clusters.</p>
      <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" alt="Helm"/>
      <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
    </td>
    <td width="33%" valign="top">
      <h3><a href="https://github.com/frappe/frappe/pull/33680">Open Source: Frappe Framework</a></h3>
      <p>Fixed phone-number validation in the Address doctype; merged into Frappe's version-15-hotfix (PR #33680) and released in v15.78.0.</p>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/Frappe-0089FF?style=flat-square" alt="Frappe"/>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://ai.adityalive.tech"><img src="https://img.shields.io/badge/🚀_Live:_Academic_Intelligence_Platform-9B2C2C?style=for-the-badge" alt="Live Academic Intelligence Platform"/></a>
  <a href="https://dev.adityalive.tech/"><img src="https://img.shields.io/badge/🚀_Live:_Hyper_Scale_Ops-430098?style=for-the-badge" alt="Live Hyper Scale Ops"/></a>
  <a href="https://p.us5.datadoghq.com/sb/8e9bd3b1-7001-11f1-aae3-c2753782a27a-994485ddc16ff7de20d382368a9bf932"><img src="https://img.shields.io/badge/Datadog_Dashboard-632CA6?style=for-the-badge&logo=datadog&logoColor=white" alt="Live Datadog dashboard"/></a>
</p>

### Highlights from the Academic Intelligence Platform

- **Verifiable answers:** page-aware chunking (600 tokens / 100 overlap) keeps exact page numbers, so every answer cites the PDF page it came from.
- **Evals that gate CI:** a RAGAS suite runs against the production `/agent` endpoint nightly and fails on a 0.05 regression. It exposed that `/agent` wasn't returning retrieved chunks, which made faithfulness a self-comparison, and an 11-turn smoke test later caught 20× response bloat that the single-turn eval missed.
- **Tenant isolation at the SQL layer:** verified in CI, where cross-tenant queries return 0 rows.
- **Async ingestion:** S3 → SQS → ECS Fargate worker with retries and a dead-letter queue.
- **Zero stored AWS credentials:** GitHub Actions deploys through OIDC (about 4 minutes including the health check).

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F1D1D,100:C8553D" alt=""/>

## Tech Stack

<div align="center">

### AI & LLM

<img src="https://img.shields.io/badge/RAG-6366F1?style=for-the-badge" alt="RAG"/>
<img src="https://img.shields.io/badge/Hybrid_Retrieval-0F766E?style=for-the-badge" alt="Hybrid Retrieval"/>
<img src="https://img.shields.io/badge/RAGAS-6366F1?style=for-the-badge" alt="RAGAS"/>
<img src="https://img.shields.io/badge/AWS_Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Bedrock"/>
<img src="https://img.shields.io/badge/AWS_Strands-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Strands"/>
<img src="https://img.shields.io/badge/Pydantic_AI-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic AI"/>
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge" alt="MCP"/>
<img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge" alt="ChromaDB"/>

### Software Engineering

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=python%2Cfastapi%2Cdjango%2Cpostgres%2Credis%2Cbash&perline=6&theme=dark"/>
  <img src="https://skillicons.dev/icons?i=python%2Cfastapi%2Cdjango%2Cpostgres%2Credis%2Cbash&perline=6&theme=light" alt="Python, FastAPI, Django, PostgreSQL, Redis, Bash"/>
</picture>

<p>
  <img src="https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic"/>
</p>

### Cloud & DevOps

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=aws%2Cdocker%2Ckubernetes%2Cterraform%2Cjenkins%2Cgithubactions%2Clinux&perline=7&theme=dark"/>
  <img src="https://skillicons.dev/icons?i=aws%2Cdocker%2Ckubernetes%2Cterraform%2Cjenkins%2Cgithubactions%2Clinux&perline=7&theme=light" alt="AWS, Docker, Kubernetes, Terraform, Jenkins, GitHub Actions, Linux"/>
</picture>

<p>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
  <img src="https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" alt="SonarQube"/>
  <img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge" alt="Trivy"/>
</p>

### Observability

<img src="https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white" alt="Datadog"/>
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
<img src="https://img.shields.io/badge/New_Relic-008C99?style=for-the-badge&logo=newrelic&logoColor=white" alt="New Relic"/>

### Tools

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=git%2Cgithub%2Cvscode%2Cpostman%2Cpycharm&perline=5&theme=dark"/>
  <img src="https://skillicons.dev/icons?i=git%2Cgithub%2Cvscode%2Cpostman%2Cpycharm&perline=5&theme=light" alt="Git, GitHub, VS Code, Postman, PyCharm"/>
</picture>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F1D1D,100:C8553D" alt=""/>

## GitHub Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/kacho_ga/0-profile-details.svg"/>
    <img width="82%" src="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/moltack/0-profile-details.svg" alt="Contribution history"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/kacho_ga/1-repos-per-language.svg"/>
    <img width="40%" src="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/moltack/1-repos-per-language.svg" alt="Top languages by repo"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/kacho_ga/2-most-commit-language.svg"/>
    <img width="40%" src="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/moltack/2-most-commit-language.svg" alt="Top languages by commit"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/kacho_ga/3-stats.svg"/>
    <img width="40%" src="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/moltack/3-stats.svg" alt="GitHub stats"/>
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/kacho_ga/4-productive-time.svg"/>
    <img width="40%" src="https://raw.githubusercontent.com/MP-30/MP-30/output/cards/moltack/4-productive-time.svg" alt="Commits by hour of day"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-streak-stats-eight.vercel.app/?user=MP-30&theme=dark&hide_border=true&ring=D9775C&fire=D9775C&currStreakLabel=D9775C"/>
    <img width="60%" src="https://github-readme-streak-stats-eight.vercel.app/?user=MP-30&theme=default&hide_border=true&ring=B4472F&fire=B4472F&currStreakLabel=B4472F" alt="GitHub streak"/>
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MP-30/MP-30/output/github-snake-dark.svg"/>
    <img width="100%" src="https://raw.githubusercontent.com/MP-30/MP-30/output/github-snake.svg" alt="Contribution snake animation"/>
  </picture>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:7F1D1D,100:C8553D" alt=""/>

## Let's Connect

<p align="center">
  <a href="https://adityalive.tech/"><img src="https://img.shields.io/badge/🌐_Portfolio-9B2C2C?style=for-the-badge" alt="Portfolio"/></a>
  <a href="https://github.com/MP-30"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="https://www.linkedin.com/in/aditya-bhadauriya-99bb8a86/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:adityabhadauriya93@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://leetcode.com/mp-30"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0%3AD9775C%2C50%3AB4472F%2C100%3A991B1B"/>
    <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0%3AB4472F%2C50%3A9B2C2C%2C100%3A7F1D1D" alt=""/>
  </picture>
</p>
