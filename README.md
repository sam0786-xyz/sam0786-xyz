<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=205&color=0:0B1220,42:123B52,100:0F9D8A&text=Mohammad%20Sameer&fontColor=F8FAFC&fontSize=49&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLM%20Systems%20%7C%20Applied%20AI%20Products&descAlignY=60&descSize=16" width="100%" alt="Mohammad Sameer | AI Engineer"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=15&duration=2800&pause=1000&color=2DD4BF&center=true&vCenter=true&width=780&lines=Engineering+AI+systems+that+solve+real+problems.;RAG+%7C+Agents+%7C+LLM+Systems+%7C+Backend.;From+data+and+models+to+APIs%2C+deployment%2C+and+users." alt="Animated engineering tagline"/>

<p>
  <a href="https://linkedin.com/in/connect-to-sam-xyz"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:tech.geek.sameer@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://sam18.xyz"><img src="https://img.shields.io/badge/Portfolio-sam18.xyz-0F766E?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://github.com/sam0786-xyz"><img src="https://img.shields.io/badge/GitHub-sam0786--xyz-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

**AI Engineer @ PrudentBit** &nbsp;·&nbsp; **B.Tech CSE (AI & ML), Sharda University** &nbsp;·&nbsp; **Delhi NCR, India**

</div>

---

## Engineering profile

I’m an AI Engineer interested in the systems behind useful AI products: retrieval, model orchestration, computer vision, backend services, data pipelines, and deployment.

I enjoy moving beyond a model/API demonstration and working through the engineering decisions that make a product usable: **data quality, interfaces, validation, security boundaries, latency, evaluation, and operational reliability**.

My strongest interests sit at the intersection of **Generative AI, applied machine learning, and software engineering**.

> **Engineering mindset:** use models where they add value; keep critical system behaviour explicit, testable, and dependable.

## Areas I work in

| Discipline | Focus |
|---|---|
| **Generative AI** | LLM applications, RAG, semantic retrieval, structured outputs, tool use, agent workflows |
| **Applied ML** | Model training and inference |
| **Backend Engineering** | Python, FastAPI, REST APIs, authentication, webhooks, asynchronous workflows |
| **Data & Automation** | Web scraping, validation, ingestion pipelines, email and event automation |
| **Cloud & Deployment** | AWS, GCP, Docker, managed databases, CI workflows |

## Some Key Projects

I keep this section focused on a small number of projects that best demonstrate research depth, end-to-end product engineering, and practical backend development.

### 01 · STP-RAG — Research & Evaluation Workbench
<a href="https://github.com/sam0786-xyz/STP_RAG_v2"><img src="https://img.shields.io/badge/Repository-STP__RAG__v2-181717?style=flat-square&logo=github" alt="STP-RAG repository"/></a>

A research-oriented RAG project exploring **adaptive chunking and selective context propagation**. The workbench is designed to compare STP-RAG against fixed-size and semantic-similarity chunking, with a focus on making retrieval behaviour inspectable rather than treating the retriever as a black box.

- Browser-based research dashboard with a chunking playground and side-by-side method comparison.
- Interactive views for chunk boundaries, semantic retrieval, and context propagation.
- Embedding-powered browser retrieval using `bge-small-en-v1.5` through Transformers.js.
- Research manuscript, implementation notes, and review-response documentation maintained alongside the workbench.

**Stack:** React · TypeScript · Vite · Transformers.js · BGE embeddings · Python research tooling

<sub>Active research project. Preliminary aggregates are not presented as independently reproduced benchmark results.</sub>

### 02 · AgentCFO — Autonomous Personal Finance Agent
<a href="https://github.com/sam0786-xyz/personal-cfo"><img src="https://img.shields.io/badge/Repository-GitHub-181717?style=flat-square&logo=github" alt="AgentCFO repository"/></a>
<a href="https://cfo.sam18.xyz"><img src="https://img.shields.io/badge/Live%20app-cfo.sam18.xyz-0F766E?style=flat-square" alt="AgentCFO live app"/></a>
<a href="https://github.com/sam0786-xyz/personal-cfo/actions/workflows/ci.yml"><img src="https://github.com/sam0786-xyz/personal-cfo/actions/workflows/ci.yml/badge.svg" alt="AgentCFO CI"/></a>

A finance agent that connects voice-driven spending decisions with transaction reconciliation from bank alert emails. Its central design choice is separating model interpretation from security-sensitive and money-critical operations.

- Voice/text spending checks through a FastAPI endpoint.
- Bank-email ingestion through Gmail, Pub/Sub, and an authenticated webhook.
- Multi-layer OTP and credential filtering before content reaches the LLM.
- Classification cascade combining learned rules, keywords, recurring patterns, LLM fallback, and human review.
- Firestore transactional updates and an append-only ledger.
- CI checks and automated tests covering security boundaries, classification, state, and decision logic.

**Stack:** Python · FastAPI · Gemini · Firestore · Gmail API · Pub/Sub · Cloud Run · pytest

### 03 · Technova — Hackathon & Technical Community Platform
<a href="https://github.com/sam0786-xyz/technova_hackathon_portal"><img src="https://img.shields.io/badge/Portal%20repository-GitHub-181717?style=flat-square&logo=github" alt="Technova portal repository"/></a>
<a href="https://www.technovashardauniversity.in/"><img src="https://img.shields.io/badge/Official%20website-Live-0F766E?style=flat-square" alt="Official Technova website"/></a>

A team-built digital platform for Technova, the technical society at Sharda University. The work brings event discovery, registration, member engagement, and organizer operations into one product.

- Event listings, registration, and custom registration forms.
- Google OAuth, onboarding, and role-based access for students, volunteers, and administrators.
- Member profiles, XP/achievements, and leaderboards.
- Admin tools for event management, user administration, feedback, and registration analytics.
- QR-based attendance scanner with real-time sync and offline queue support.

**Stack:** Next.js · TypeScript · Supabase · PostgreSQL · NextAuth.js · Tailwind CSS · Framer Motion

<sub>Team project. The portal repository is maintained separately from the live society website.</sub>

### 04 · Internship Tracker — Automated Attendance & Work Journal
<a href="https://github.com/sam0786-xyz/internship_tracker"><img src="https://img.shields.io/badge/Repository-GitHub-181717?style=flat-square&logo=github" alt="Internship Tracker repository"/></a>

A personal internship productivity platform that combines **automatic office attendance, a daily work journal, and AI-generated progress summaries** in one mobile-friendly web application.

- **Location-triggered check-in and check-out:** iPhone Shortcuts detect arrival at and departure from the office and automatically call the backend, reducing the need to remember attendance actions manually.
- **Manual fallback:** attendance can still be recorded manually if a location automation does not run.
- **Reliable attendance records:** FastAPI endpoints handle check-in/check-out events, prevent duplicate submissions through idempotent operations, and store server-side timestamps.
- **Daily work journal:** record what was worked on each day, keeping a structured history of internship tasks and progress.
- **LLM-powered summaries:** generate summaries for a day, week, month, or custom date range using the saved work logs, making it easier to prepare accurate internship reports and evaluations.
- **Mobile-first workflow:** designed around iPhone Shortcuts and a web interface rather than requiring a separate native iOS app.

**Stack:** Python · FastAPI · Supabase · PostgreSQL · iOS Shortcuts · LLM integration

---

## Experience

### AI Engineer · PrudentBit
**October 2026 – Present**

Contributing to **ImmuneFiles-PII**, a privacy-focused document intelligence platform. My work spans production hardening of the v1 services and the development of v2, which combines a customer-specific privacy vault with an agentic document analyst designed to keep personal data away from the language model.

- **Production hardening (v1):** improved PII detection and whole-word/Markdown redaction; added SSRF-safe file downloads, service-prefixed API routes, Nginx paths, per-service health endpoints, production worker deployment, CI/CD, and Sentry error reporting.
- **Privacy vault (ImmuneShield v2):** implemented stable per-customer placeholders across files, customer-specific encryption keys, permission-controlled reveal, audited administrative reveal, and an outgoing prompt scan before content reaches the model.
- **Agentic document analyst (ImmuneTalk v2):** built a LangGraph workflow that routes questions, plans multi-step tasks, and uses 17 tools for document search, tables, calculations, timelines, comparisons, checklists, charts, and Excel outputs.
- **Retrieval and answer quality:** migrated retrieval from Pinecone to PostgreSQL/pgvector, added source-checked answer citations, a stronger-model retry path for weak answers, multilingual search, document version support, and retrieval evaluation with a golden set.
- **LLM platform and operations:** integrated LiteLLM with OpenRouter, retries and provider fallback, per-tenant budgets, Langfuse tracing, Prometheus metrics, usage metering, load testing, and a v1-to-v2 customer migration tool.
- **Enterprise controls:** implemented Free, Pro, and Enterprise plan limits, configurable customer-owned models running in their own cloud, and an Enterprise AI spend cap.

**Selected validation:** the v2 final build passed all 12 quality gates and 510 automated tests. On the documented evaluation set, it achieved 95.6% correct answers across 45 single-document questions and 87% across 100 multi-file questions; 40/40 security attacks in the test suite were blocked. These are project evaluation results, not claims of independently audited production performance.

**Status:** v1 hardening is in production. v2 is built and tested on the `feat/agentic-v2` branch and is awaiting hosting and integration; it has not been represented as live production functionality.

### Generative AI Developer Intern · KlipKanvas
<sub>Formerly AIZoned · Completed July 2026</sub>

Contributed to an AI-powered CA exam-preparation platform across AI workflows, backend services, and product development.

- Worked with **Next.js, FastAPI, AWS, Gemini, and Qdrant**.
- Contributed to semantic retrieval for study-material discovery.
- Worked on AI-assisted answer-sheet evaluation workflows.
- Built voice-oriented conversational workflows using **ElevenLabs and Twilio**.
- Developed backend APIs and integrations involving **JWT authentication and DynamoDB**.

## Community & leadership

- **MLOps Community, Delhi NCR** — Volunteer supporting local technical learning and community engagement.
- **Databricks User Group, Noida** — Organizer contributing to community events and knowledge sharing.
- **Technova Society, Sharda University** — Student leadership and technical event organization, including the Technovation Hackathon, which attracted 2,400+ participants.

The official [Technova website](https://www.technovashardauniversity.in/) brings together the society's clubs, events, leadership, and student community. My involvement has included technical society initiatives, event execution, and platform work with the student team.

## Technology

<p><strong>Languages</strong><br/>
<img src="https://skillicons.dev/icons?i=python,cpp,java,js,ts,sql,bash,html,css" alt="Python, C++, Java, JavaScript, TypeScript, SQL, Bash, HTML and CSS"/></p>

<p><strong>AI, ML & computer vision</strong><br/>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv" alt="PyTorch, TensorFlow and OpenCV"/>
<img src="https://img.shields.io/badge/Google%20Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=chainlink&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" alt="Qdrant"/>
<img src="https://img.shields.io/badge/Ultralytics%20YOLO-111111?style=flat-square" alt="Ultralytics YOLO"/></p>

<p><strong>Backend & frontend</strong><br/>
<img src="https://skillicons.dev/icons?i=fastapi,flask,nodejs,react,nextjs,tailwind" alt="FastAPI, Flask, Node.js, React, Next.js and Tailwind"/></p>

<p><strong>Cloud, data & developer tools</strong><br/>
<img src="https://skillicons.dev/icons?i=aws,gcp,azure,docker,linux,git,github,postgres,mongodb" alt="AWS, GCP, Azure, Docker, Linux, Git, GitHub, PostgreSQL and MongoDB"/>
<img src="https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firestore"/>
<img src="https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white" alt="DynamoDB"/></p>

<p><strong>Voice & automation</strong><br/>
<img src="https://img.shields.io/badge/ElevenLabs-111111?style=flat-square" alt="ElevenLabs"/>
<img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white" alt="Twilio"/>
<img src="https://img.shields.io/badge/Google%20Cloud%20Pub%2FSub-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud Pub/Sub"/></p>

<details>
<summary><strong>What I’m currently sharpening</strong></summary>

- RAG quality, retrieval evaluation, and grounding.
- Agent workflows, structured outputs, and reliable tool execution.
- Backend architecture, concurrency, and distributed systems fundamentals.
- Secure AI integrations and deterministic safeguards.
- MLOps, deployment patterns, and cloud infrastructure.
- Data structures, algorithms, and system design.

</details>

## GitHub activity

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=sam0786-xyz&show_icons=true&hide_border=true&theme=transparent&rank_icon=github&include_all_commits=true" alt="GitHub statistics"/>
  <img height="165" src="https://streak-stats.demolab.com?user=sam0786-xyz&hide_border=true&theme=transparent" alt="GitHub contribution streak"/>
  <img width="58%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sam0786-xyz&layout=compact&hide_border=true&theme=transparent&langs_count=8" alt="Most used languages"/>
</div>
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=sam0786-xyz&theme=github-compact&hide_border=true&area=true" width="100%" alt="Contribution activity graph"/>
</div>

## Connect

I’m interested in conversations around AI engineering, LLM systems, applied ML, backend architecture, and building products with thoughtful engineering.

- **Portfolio:** [sam18.xyz](https://sam18.xyz)
- **LinkedIn:** [linkedin.com/in/connect-to-sam-xyz](https://linkedin.com/in/connect-to-sam-xyz)
- **Email:** [tech.geek.sameer@gmail.com](mailto:tech.geek.sameer@gmail.com)
- **GitHub:** [github.com/sam0786-xyz](https://github.com/sam0786-xyz)

<div align="center">

<img src="https://komarev.com/ghpvc/?username=sam0786-xyz&label=PROFILE%20VIEWS&color=0F766E&style=flat-square" alt="Profile views"/>

**Build systems people can rely on. Make AI earn its place in the product.**

<img src="https://capsule-render.vercel.app/api?type=waving&height=95&section=footer&color=0:0B1220,100:0F9D8A" width="100%" alt="Footer wave"/>

</div>
