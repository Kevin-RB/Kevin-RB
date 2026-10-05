<h1 align="center">Hi, I'm Kevin Romero 👋</h1>

<p align="center">
  <a href="https://github.com/Kevin-RB"><img src="https://img.shields.io/badge/-Kevin--Romero-2ea44f?style=flat-square&logo=github" alt="Kevin Romero" /></a>
  <a href="https://www.linkedin.com/in/kevinromerob/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center">
  <b>Software Engineer</b> &nbsp;|&nbsp; <b>AI Product Engineer</b> &nbsp;·&nbsp; MIT (Australia) 🇦🇺 🦘
</p>

<p align="center">
  <a href="#projects">Featured Projects</a> ·
  <a href="#stack">Stack</a> ·
  <a href="#connect">Connect</a>
</p>

---

## About Me

I love building things that actually work — especially when software engineering meets AI. I recently completed a **Master of Information Technology (MIT) in Australia** (super proud of it btw 🦘), which is where the "MIT" on my profile comes from.

Most of my work right now is agentic AI: pipelines that pull structure out of messy, unstructured documents, and local-first apps that keep your data on your own machine. I care about durable workflows, clean domain models, and shipping things that survive contact with real users.

What that means in practice is owning problems end to end — the domain model, the architecture, the prompt and eval strategy, the interface, and the deployment. Most of my projects are things I designed, built, and shipped myself rather than inherited from a spec.

## <a name="projects"></a>Featured Projects

### 📸 [local-receipt](https://github.com/Kevin-RB/local-receipt)

**Local-first receipt AI analyser.** Photograph a paper receipt and it becomes structured, persistent data — merchant, line items, totals, GST, and transaction date. Nothing leaves your machine: a durable background workflow extracts the data using local vision/language models, stores the image in S3-compatible object storage, and the UI updates live as processing progresses. Line items that don't sum to the stated total get flagged rather than silently accepted.

**Stack:** Next.js 16 (App Router) · React 19 · TypeScript · Tailwind CSS 4 · shadcn/ui · Drizzle ORM · Postgres · RustFS (S3-compatible) · Inngest (durable jobs + realtime) · AI SDK · Better Auth · Docker Compose · Vitest

[![local-receipt](https://img.shields.io/badge/repo-Kevin--RB%2Flocal--receipt-2ea44f?style=flat-square)](https://github.com/Kevin-RB/local-receipt)

### 🕸️ [crdc-workflows](https://github.com/Kevin-RB/crdc-workflows)

**Mastra pipelines that turn source documents into knowledge graphs.** A four-stage workflow — chunking, entity extraction, relation extraction, and Neo4j ingest — that reads parsed documents and produces a queryable entity-relation graph. Each stage persists its state to disk, so you can resume, re-run a single failed chunk, or swap in a different LLM provider without starting over. Includes a chat agent, a supervisor agent, and Mastra Studio for running everything interactively.

**Stack:** TypeScript · Mastra (agents, workflows, RAG, memory, evals) · Neo4j · DuckDB / libSQL · Zod · LM Studio (local OpenAI-compatible LLM) · Docker · pnpm

[![crdc-workflows](https://img.shields.io/badge/repo-Kevin--RB%2Fcrdc--workflows-2ea44f?style=flat-square)](https://github.com/Kevin-RB/crdc-workflows)

## <a name="stack"></a>Stack

**Languages** TypeScript · JavaScript · SQL · Python

**Frontend** React · Next.js · Tailwind CSS · shadcn/ui

**Backend** Node.js · REST · Server Actions · Drizzle ORM · Postgres

**AI & Agents** Mastra · AI SDK · Inngest · RAG · Knowledge Graphs · LM Studio

**Infrastructure** Docker · Docker Compose · Neo4j · S3-compatible storage · Coolify

**Tooling** pnpm · Vitest · Biome / Ultracite · GitHub Actions

## <a name="connect"></a>Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevinromerob/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/kevinromero.b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kevin-RB)

---

<p align="center">
  <sub>Made with ☕ in Brisbane, Australia</sub>
</p>
