# IE-Insight: Industrial Engineering Chatbot Platform

> A fully automated, scalable, API-driven AI chatbot platform for Industrial Engineering knowledge.

---

## 🚀 Overview
**IE-Insight** is a next-gen AI platform built to democratize access to Industrial Engineering knowledge through an LLM-powered chatbot. It's designed with a full **DevOps + TechOps stack**, enabling seamless deployment, scaling, observability, and retraining — all controlled through APIs.

---

## 🧠 Powered By

| Technology | Role |
|------------|------|
| ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white) | Backend API Framework |
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) | Containerization |
| ![Kubernetes](https://img.shields.io/badge/Kubernetes-326ce5?style=for-the-badge&logo=kubernetes&logoColor=white) | Orchestration |
| ![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white) | K8s Package Manager |
| ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) | CI/CD |
| ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) | Infrastructure as Code |
| ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) | Monitoring |
| ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) | Dashboards |
| ![ELK Stack](https://img.shields.io/badge/ELK_Stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white) | Logging |
| ![Langchain](https://img.shields.io/badge/Langchain-000000?style=for-the-badge&logo=data:image/svg+xml;base64,&logoColor=white) | LLM Orchestration |
| ![Pinecone](https://img.shields.io/badge/Pinecone-45A29E?style=for-the-badge&logo=data:image/svg+xml;base64,&logoColor=white) | Vector DB |
| ![Auth0](https://img.shields.io/badge/Auth0-EB5424?style=for-the-badge&logo=auth0&logoColor=white) | Auth and RBAC |
| ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white) | DNS + HTTPS |

---

## 🧩 Other AI Tools Used

| Tool | Purpose |
|------|---------|
| 💡 [Lovable](https://lovable.so) | Branding, storytelling, and user psychology insights |
| ⚡ [bolt.new](https://bolt.new) | Workflow automation & lightweight product experimentation |
| 🧠 [ChatGPT](https://chat.openai.com) | LLM guidance, prototyping, architectural brainstorming |
| 🧾 [NotebookLM](https://notebooklm.google) | Document-based knowledge management and cross-referencing |
| 🤖 [Hugging Face](https://huggingface.co) | Model experimentation, training, deployment |
| 💻 [Trae IDE](https://trae.codes) / [Cursor](https://www.cursor.so) | AI-powered coding and debugging |

---

## 🧱 Features

- ✅ Fine-tuned LLM chatbot on IE knowledge
- ✅ Upload PDFs and retrain on the fly
- ✅ Fully containerized microservices
- ✅ API-first deployment & retraining
- ✅ Real-time monitoring & alerting
- ✅ CI/CD pipeline for GitOps style DevOps
- ✅ RBAC-secured user management

---

## 📚 Domains Covered

- Supply Chain Management
- Work-Study & Ergonomics
- Quality Control & TQM
- Lean & Six Sigma
- Operations Research
- Inventory & Production Planning
- Facility Layout
- Industry 4.0 & Smart Manufacturing

---

## 🔗 API Workflow
| Action | API Call |
|--------|----------|
| Deploy new version | `POST /deploy` |
| Add PDF to chatbot memory | `POST /train` |
| Rotate secrets | `POST /rotate-secrets` |
| Monitor metrics | `GET /metrics` |
| Debug chat logs | `GET /logs?user_id=X` |

---

## 📊 Workflow Flowchart

```mermaid
graph TD
  A[User] --> B[Frontend (Next.js)]
  B --> C[FastAPI Gateway]
  C --> D[Chatbot Microservice]
  C --> E[Metrics API / Logs API]
  D --> F[Vector DB (Pinecone/Weaviate)]
  D --> G[Fine-tuned LLM Model]
  C --> H[API Gateway / Load Balancer]
  H --> I[Kubernetes Cluster]
  I --> J[Helm Deployed Services]
  J --> K[Monitoring (Prometheus + Grafana)]
  J --> L[Logging (ELK / Loki)]
  I --> M[Terraform-Provisioned Infra]
  M --> N[Cloudflare + DNS]
  O[CI/CD (GitHub Actions + ArgoCD)] --> I
```
D)] --> I
```

---

## 🏗️ Project Status: MVP Stage

| Status | Description |
|--------|-------------|
| ✅ | Base chatbot logic with PDF training |
| ✅ | Kubernetes + GitHub Actions in place |
| 🔄 | Vector DB integration & LLM fine-tuning |
| 🔄 | Production-level CI/CD testing |

---

## 🌟 Vision
IE-Insight will become the go-to AI expert for Industrial Engineers — replacing static PDFs, lecture slides, and scattered notes with an always-on, intelligent, API-first assistant.

---

> Built by Garv | Let’s automate Industrial Engineering education, the TechOps way ⚙️
