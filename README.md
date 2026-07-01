# Prathmesh Desai

> I build systems that handle real load — async pipelines, distributed backends, and infra that fails gracefully. I care about why architectural decisions matter, not just that they work.

🎓 B.Tech Computer Science — SRM University, KTR (2023–2027)  
🏆 Technical Lead — Directorate of Student Affairs (Milan '25 & '26)  
☁️ Cloud and DevOps Manager — Amazon Student Builder Group, SRMIST  
📫 prathmeshpdesai@gmail.com &nbsp;|&nbsp; 🌐 [ct-os-dev-portfolio.vercel.app](https://ct-os-dev-portfolio.vercel.app)

---

## ⚡ Production Metrics (Milan Platform)

> 5,400+ passes sold · 4K+ concurrent users · ₹0 payment failures · 99.9% uptime  
> AWS EC2 + PM2 + Prometheus + Grafana + Loki · Dual auth: Google OAuth + custom OTP · ~60-70MB Node.js footprint

---

## 🚀 Production Systems

| Project | What it is | Status |
| :--- | :--- | :--- |
| **[Milan Core Platform](https://www.srmmilan.in)** | Festival ticketing — 5,400+ paid tickets, 4K+ concurrent users, ₹0 payment failures | 🏁 Operated & Retired |
| **[AdvGuard](https://github.com/pd241008/Adv-Guard)** | Adversarial ML defense — DACM algorithm for structurally valid tabular perturbations, async RabbitMQ retraining, FGSM/PGD/JSMA on NSL-KDD & CICIDS2017 | 🏁 Research Complete |
| **[DevTrace](https://github.com/pd241008/DevTrace)** | Rust observability engine — Tokio MPSC ingestion (10k buffer), SQLite event store, CQRS architecture. Ships on `npm`, `cargo`, `pip`, `go install` | ✅ Live · Multi-Platform |
| **[ExpressKit CLI](https://www.npmjs.com/package/@pd241008/expresskit)** | Convention-driven Express scaffolding. `npx @pd241008/expresskit init` | ✅ Live on npm |
| **[NeoUI](https://www.npmjs.com/package/@pd241008/neoui)** | Neo-brutalist component library — Rust-based CLI, Radix UI primitives, Vitest + Storybook | ✅ Live on npm |
| **[Gamify](https://gamify-t8cn.vercel.app/)** | Serverless esports analytics — Go + GitHub Actions cron ingestion, Cassandra time-series, Upstash QStash zero-worker notifications | ✅ Live |
| **[Taskiee](https://github.com/pd241008/Taskiee)** | RBAC task management — PRESIDENT/ADMIN/Developer hierarchy, dnd-kit Kanban, built in ~3 days on NeoUI + ExpressKit | ✅ Live |
| **[ctOS Portfolio](https://ct-os-dev-portfolio.vercel.app)** | Terminal-based portfolio. The terminal IS the router. | ✅ Live |
| **[Gram Sevak](https://github.com/pd241008/Gram-Sevak)** | NLP complaint management — keyword categorization, voice complaint metadata, Express + FastAPI + Next.js | ✅ Live |
| **[AQI Prediction Engine](https://aqi-preditcion-model.vercel.app/)** | Full MLOps loop — Decision Tree on CPCB data, FastAPI on HuggingFace, Gemini synthetic data | ✅ Live |
| **[NeuroTrack](https://neuro-track-lime.vercel.app/)** | AI wellness dashboard with semantic journal search | ✅ Live |
| **[NEURO](https://github.com/pd241008/Neuro)** | Zero-trust polyglot compiler — C# recursive descent parser → Rust security auditor → C++ LLVM IR translator. Mathematically guarantees memory safety before codegen | ✅ Live |

---

## 📄 Research

| Project | What it explores | Status |
| :--- | :--- | :--- |
| **Proactive Adversarial Defense Framework Integrating Lifecycle Robustness in Machine Learning Models for Cybersecurity** | Introduces **DACM (Discrete Adversarial Constraint Mapping)** — maps continuous adversarial gradients onto structurally valid discrete categorical boundaries, enabling real-world executable payloads against tabular network telemetry. Validated on NSL-KDD and CICIDS2017; adversarially trained model sustains **93.00% robust accuracy** at ε = 0.15. Implementation: [AdvGuard](https://github.com/pd241008/Adv-Guard). | ✅ Accepted |
| **MIDAS (Micro-Inference Defense with Adaptive State)** | Adaptive-state adversarial defense for constrained embedded inference, explored across two hardware tracks: a Rust multi-threaded pipeline on ARM Cortex-A76 (Raspberry Pi 5), and a bare-metal C implementation on ARM Cortex-M4 (STM32F4) with dedicated hardware characterization. | 🔨 In Progress |
| **SentinelMesh** | Gossip-protocol-based distributed anomaly detection system for collective, decentralized network defense, evaluated on UNSW-NB15. Full draft with results tables complete. | 🔨 In Progress |

---

## 🚢 Active Development

| Project | What it is | Status |
| :--- | :--- | :--- |
| **[IntelliDoc](https://github.com/pd241008/IntelliDoc-Query)** | Async document intelligence — OCR → Celery → Semantic Indexing pipeline | 🚢 Shipping |
| **[Supply Chain Risk Intelligence](https://github.com/jaxcode23/Multi-Agent-Supply-Chain-Risk-Intelligence-System)** | Multi-agent AI platform — Go scraping gateway, Scala ZIO/Akka hub, Python RAG agents, Rust orchestrator, Neo4j supplier graph | 🔨 Building |
| **ClipSync** | Two-way push-based clipboard sync between Windows and WSL2 — Rust orchestration layer, C++ shared-memory/spinlock core (mmap'd backing file), Raylib visualization | 🔨 Building |
| **Aegis** | Distributed telemetry — Go ring-buffer edge agents, Scala/Akka actor brain, RAG briefings via gRPC/Protobuf | 🔨 Building |
| **OmniStat** | Polyglot observability pipeline — Scala GitHub GraphQL ingestion, Go BFF gateway, neo-brutalist terminal HUD | 🔨 Building |
| **PrimeVector** | Go LSH vectorization engine — cosine similarity, Kafka → Protobuf → Scala risk pipeline | 🔨 Building |
| **Pikernal** | Minimal RTOS-style Raspberry Pi kernel, derived from NEURO's runtime research | 📐 Designing |

---

## 🗺️ Planned & Exploratory

> These are architecture explorations and designs-in-progress — not active codebases. Some will ship, some won't. Documented here for transparency.

| Project | Concept | Stage |
| :--- | :--- | :--- |
| **Project Omega** | Distributed ledger — CQRS, Event Sourcing, Raft consensus | 🔨 Building |
| **SyntaxFlow** | Text-to-diagram engine — Go/TinyGo WASM parser, DFS cycle breaking, A* orthogonal routing | 📐 Designing |
| **CodeQuest** | Gamified backend learning — Docker + gVisor containers, Monaco Editor, hidden integration tests | 📐 Designing |
| **NeoShell** | Zero-config Neovim IDE host via DevTrace event bus | 📐 Designing |
| **CollabStory** | Real-time branching narrative — Convex reactive backend, DAG story structure | 📐 Designed |
| **IntelliVOD** | Semantic video library — timestamp-level search across transcriptions | 📐 Designed |

> Full architecture docs and system designs: **[ct-os-dev-portfolio.vercel.app](https://ct-os-dev-portfolio.vercel.app)**

---

## 💻 Tech Stack

### 🧠 Languages
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) 
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) 
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) 
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) 
![Scala](https://img.shields.io/badge/scala-%23DE3423.svg?style=for-the-badge&logo=scala&logoColor=white) 
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) 
![Kotlin](https://img.shields.io/badge/kotlin-%237F52FF.svg?style=for-the-badge&logo=kotlin&logoColor=white) 
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)

### ⚙️ Backend & APIs
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) 
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) 
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) 
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) 
![RabbitMQ](https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) 
![Celery](https://img.shields.io/badge/celery-%2337814A.svg?style=for-the-badge&logo=celery&logoColor=white) 
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) 
![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) 
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) 
![Clerk](https://img.shields.io/badge/Clerk-%236C47FF.svg?style=for-the-badge&logo=clerk&logoColor=white) 
![Convex](https://img.shields.io/badge/Convex-%23EA422A.svg?style=for-the-badge&logo=convex&logoColor=white)

### 🗄️ Database & Cloud Infra
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) 
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) 
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) 
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white) 
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) 
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) 
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) 
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)

### 🛡️ DevOps & Observability
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) 
![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) 
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white) 
![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white) 
![Sentry](https://img.shields.io/badge/sentry-%23362D59.svg?style=for-the-badge&logo=sentry&logoColor=white) 
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) 
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) 
![NeoVim](https://img.shields.io/badge/NeoVim-%2357A143.svg?style=for-the-badge&logo=neovim&logoColor=white)

### 🎨 Frontend
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) 
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) 
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) 
![DaisyUI](https://img.shields.io/badge/daisyui-5A0EF8?style=for-the-badge&logo=daisyui&logoColor=white) 
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) 
![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=for-the-badge&logo=tauri&logoColor=%23FFFFFF) 
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

---

## 📊 GitHub Stats

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=pd241008&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
    </td>
    <td>
      <img src="https://streak-stats.demolab.com?user=pd241008&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=pd241008&theme=tokyonight&hide_border=true&layout=compact" alt="Top Languages" />
    </td>
  </tr>
</table>

---

## 🌐 Socials

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/prathmesh_1d) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/prathmesh-desai-288656288) 
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:prathmeshpdesai@gmail.com)

---

*If you read the source code of something I built and found something interesting — that was intentional.*
