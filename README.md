<!-- Header -->
<div align="center">

# Sushanth Kakarlapudi

**Senior Lead Software Engineer · AI & Distributed Systems**

*Frisco, TX · 14+ years building at Fortune 500 scale*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_HANDLE)
[![Email](https://img.shields.io/badge/sushanthk.1188%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sushanthk.1188@gmail.com)
[![GitHub](https://img.shields.io/github/followers/shawnk1188?label=Follow&style=flat-square&logo=github)](https://github.com/shawnk1188)
![Views](https://komarev.com/ghpvc/?username=shawnk1188&style=flat-square&label=profile+views)

</div>

---

## About

I architect and ship large-scale distributed systems and AI-driven solutions across Fortune 500 environments — Walmart, American Airlines, USAA, AT&T, Wells Fargo, and Verizon.

My work sits at the intersection of **data engineering, backend systems, and applied AI**. At Walmart I led a recommendation engine that contributed to a **$750M increase in eCommerce sales**. At American Airlines I drove a microservices migration that hit **99.9% uptime** and cut data retrieval time by 35%.

But beyond the day job — I build. Nights and weekends you'll find me exploring agentic AI systems, wiring up LLMs to real tools, and pushing frameworks like Google ADK into production-shaped projects. This GitHub is where that personal engineering curiosity lives.

---

## Stack

**AI & Agents**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=flat-square&logo=google&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%20Flash-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Scala](https://img.shields.io/badge/Scala-DC322F?style=flat-square&logo=scala&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Data Engineering**

![Apache Beam](https://img.shields.io/badge/Apache%20Beam-FFAB00?style=flat-square&logo=apache&logoColor=black)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Dataflow](https://img.shields.io/badge/GCP%20Dataflow-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

**Cloud & Infrastructure**

![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Podman](https://img.shields.io/badge/Podman-892CA0?style=flat-square&logo=podman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Career Highlights

| Company | Role | Impact |
|---------|------|--------|
| **Walmart Global Tech** | Senior Lead SWE | $750M eCommerce uplift via recommendation engine · AI agent cut bug resolution 30% |
| **American Airlines** | Senior Lead SWE | 99.9% uptime · 35% faster data retrieval · async microservices for millions of users |
| **USAA** | Senior SWE | Monolith → event-driven Kafka migration · OAuth2 / CyberArk security architecture |
| **AT&T** | Senior SWE | Auth redesign · Spring microservices · mentored team on microservice design patterns |
| **Early Career** | SWE | Wells Fargo · Verizon · TMG Health · University of South Alabama |

---

## Personal AI Projects

> This is where I experiment — no sprints, no tickets, just curiosity-driven engineering.

### docpilot — Production RAG system
Built a three-phase RAG system measuring 2x retrieval improvement
(0.465 → 0.992) with hybrid BM25 + vector search and cross-encoder reranking.
Evaluated with faithfulness 0.745 and context precision 0.840.


→ [View repository](https://github.com/shawnk1188/docpilot)

### LLM Task Manager
A production-grade conversational task manager powered by **Google ADK + Gemini Flash**.
Talk to your lists through a chat interface — no forms, no clicks.

**Stack:** FastAPI · Google ADK · Gemini 2.0 Flash Lite · Redis · Streamlit · Podman Compose

```
"Create a list called Groceries"  →  agent calls create_list tool  →  Redis stores it
"Add milk to Groceries"           →  agent calls add_item tool     →  done in one message
```

- Module-level ADK Runner singleton for persistent session state
- Full REST API with Prometheus metrics and Redis persistence
- Containerised with Podman Compose — one command to run locally
- Exponential backoff retry on Gemini rate limits

→ [View repository](https://github.com/shawnk1188/llm-task-manager)

---

## Certifications

![GenAI Leader](https://img.shields.io/badge/Generative%20AI%20Leader-Google-4285F4?style=flat-square&logo=google&logoColor=white)
![GCP Architect](https://img.shields.io/badge/GCP%20Professional%20Cloud%20Architect-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![GenAI LLMs](https://img.shields.io/badge/Generative%20AI%20with%20LLMs-Coursera-0056D2?style=flat-square&logo=coursera&logoColor=white)
![ML Specialization](https://img.shields.io/badge/ML%20Specialization-DeepLearning.AI-FF6F00?style=flat-square&logo=coursera&logoColor=white)
![AWS Dev](https://img.shields.io/badge/AWS%20Developer%20Associate-232F3E?style=flat-square&logo=amazonaws&logoColor=white)

---

## GitHub Stats

<div align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=shawnk1188&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shawnk1188&layout=compact&theme=default&hide_border=true&langs_count=6" />
</div>

---

## What I'm Exploring Next

- Multi-agent systems with shared memory and tool delegation
- RAG pipelines over enterprise knowledge bases
- LLM evaluation frameworks for production reliability

---

<div align="center">
  <sub>14 years of production engineering · currently building AI systems personally and professionally</sub>
  <br/>
  <sub>Open to Staff / Principal Engineer and AI Engineering Lead roles</sub>
</div>
