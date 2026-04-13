<div align="center">

# عمار كروش — Ammar Karoush

### AI & Backend Solutions Engineer

*Turning complex data challenges into scalable, intelligent systems*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=notion&logoColor=white)](https://notion.so)

</div>

---

## 👤 About Me

I'm an **AI & Backend Solutions Engineer** specializing in the full lifecycle of intelligent data systems — from distributed data acquisition at scale, to AI-powered processing pipelines that deliver decisions in under 3 seconds.

My work sits at the intersection of **backend engineering** and **applied AI**: I design systems that don't just collect data — they understand it, structure it, and act on it. Whether it's building a scraping engine across 40 dynamic sources or wiring a Llama 3 intent-recognition backend into a production SaaS, I focus on one outcome: **business value through engineering precision**.

```
Core Principle: Every system I build is designed for three non-negotiables —
                Scalability · Latency < 3s · Security
```

**Current Focus Areas:**
- 🔩 Building **FastAPI** microservices with full async architecture
- 🤖 Designing **RAG pipelines** and LLM integration layers (Llama 3, OpenAI, Groq)
- 🕸️ Engineering **distributed data acquisition** systems resilient to anti-scraping measures
- 📐 Bridging **unstructured data** into clean, AI-ready structured formats

**Background:**
- 🎓 B.Sc. in Computer Science — Menoufia National University *(in progress)*
- 🏅 IBM Data Science Specialist — **DEPI Initiative**

---

## 🧰 Technical Toolbox

### Languages

| Language | Level | Primary Use |
|---|---|---|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) **Python** | Expert | AI pipelines, backend systems, data engineering |
| ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) **SQL** | Proficient | Data modeling, complex queries, analytics |

---

### AI & Backend Engineering

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Llama3](https://img.shields.io/badge/Llama_3-7C3AED?style=for-the-badge&logo=meta&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Groq](https://img.shields.io/badge/Groq_API-F55036?style=for-the-badge&logo=groq&logoColor=white)

| Technology | Capability |
|---|---|
| **FastAPI** | Async REST APIs, middleware, dependency injection, production deployments |
| **Llama 3** | Local inference, intent recognition, fine-tuning pipelines |
| **RAG Systems** | Vector stores, embedding pipelines, retrieval-augmented generation |
| **OpenAI / Groq APIs** | LLM orchestration, prompt engineering, multi-model routing |

---

### Data Engineering & Acquisition

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-FF6B35?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

| Technology | Capability |
|---|---|
| **Playwright** | Dynamic JS rendering, headless automation, anti-detection patterns |
| **BeautifulSoup** | HTML parsing, schema extraction, data normalization |
| **Pandas** | Data transformation, cleaning pipelines, analytical workflows |
| **PostgreSQL** | Relational modeling, indexing strategies, async queries (asyncpg) |

---

### Infrastructure & Tooling

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🚀 Featured Projects

### 01 — Distributed Data Intelligence Engine
> *Unified acquisition layer across 40 heterogeneous dynamic sources*

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-FF6B35?style=flat-square)
![Async](https://img.shields.io/badge/Async-Architecture-6D28D9?style=flat-square)

**The Challenge:** 40 dynamic sources — each with distinct HTML structures, JavaScript rendering requirements, and active anti-scraping defenses (Captcha, IP blocking, rate limiting).

**The Engineering:** A config-driven, modular scraping architecture where each source is defined in an independent YAML file. Adding a new source requires zero core changes. A layered execution model separates acquisition (Playwright), parsing (BS4), and normalization into independent, testable components.

**Key Results:**
- ✅ 40 active sources maintained from a single unified codebase
- ✅ New source onboarding in **< 30 minutes** (config-only, no code)
- ✅ Extraction success rate **> 92%** with adaptive retry + exponential backoff
- ✅ Output: **Clean Structured JSON** — AI-pipeline-ready

---

### 02 — JobFlow AI — Async SaaS Intelligence Platform
> *FastAPI backend with Llama 3 intent recognition and sub-3-second response guarantee*

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Llama3](https://img.shields.io/badge/Llama_3-7C3AED?style=flat-square&logo=meta&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Async](https://img.shields.io/badge/Fully_Async-009688?style=flat-square)

**The Challenge:** Build an AI-powered task automation platform that handles high concurrent load while maintaining sub-3-second latency — without routing sensitive data through external APIs.

**The Engineering:** Fully async FastAPI backend (zero blocking I/O) paired with locally-deployed Llama 3 for intent classification. Requests are routed dynamically based on recognized intent — no brittle if-else chains. Horizontal scale-out via Uvicorn workers requires no code changes.

**Key Results:**
- ✅ **P95 latency < 3 seconds** under concurrent load
- ✅ Intent recognition accuracy **> 89%**
- ✅ **Zero data leakage** — local LLM inference, no external API dependency
- ✅ Horizontal scalability with no architectural rewrites

---

## 📊 GitHub Stats

<div align="center">

![Ammar's GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🤝 Let's Build Together

> **I work as a technical partner for startups and product teams** — not just a developer who ships code, but an engineer who understands business constraints, designs for scale from day one, and translates vague data problems into production-ready intelligent systems.
>
> If you're building something that needs to **ingest messy data at scale**, **make AI-powered decisions fast**, or **integrate LLMs into a real product** — let's talk.

<div align="center">

[![Let's Connect](https://img.shields.io/badge/Open_to_Collaboration-2EAD33?style=for-the-badge&logo=handshake&logoColor=white)](mailto:your@email.com)

*Available for freelance projects · Technical consulting · AI/Backend co-founding roles*

</div>

---

<div align="center">
<sub>Built with precision · Designed for scale · Focused on outcomes</sub>
</div>
