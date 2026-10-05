<h1 align="center">Hi, I'm Kevin Romero 👋</h1>

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

I love building things that actually work — especially when software engineering meets AI. I recently completed a **Master of Information Technology (MIT) in Australia** (super proud of it btw 🦘).

My focus is building systems and products that deliver actual value. I care about making things genuinely useful to the person using them, and a pleasure to use.

What draws me in is the machinery underneath: system design, architecture, and how a product behaves under real use and real load. I like owning the whole stack of concerns — data models, durable workflows, auth, storage, realtime, deployment — and thinking about how the pieces interact and where the failure modes hide.

AI is a tool I reach for when it's genuinely the right tool for a problem, not the premise I'm starting from. Recent projects have leaned on document and data extraction pipelines, but that's a slice of what I do, not the definition of it.

Most of my projects are things I designed, built, and shipped end to end rather than inherited from a spec.

## <a name="projects"></a>Featured Projects

### 📸 [local-receipt](https://github.com/Kevin-RB/local-receipt)

**Local-first receipt AI analyser.** Photograph a receipt and it becomes structured, persistent data — merchant, line items, totals, GST, and date — extracted by local vision models and stored with the original image. Durable background jobs, live progress updates, and integrity warnings when line items don't sum to the stated total.

**Stack:** Next.js 16 (App Router) · React 19 · TypeScript · Tailwind CSS 4 · shadcn/ui · Drizzle ORM · Postgres · RustFS (S3-compatible) · Inngest (durable jobs + realtime) · AI SDK · Better Auth · Docker Compose · Vitest

🌐 **Try it live:** [receipts.tribi.dev](https://receipts.tribi.dev) — it runs behind an invite code, so [reach out to me](https://www.linkedin.com/in/kevinromerob/) if you'd like access.

[![local-receipt](https://img.shields.io/badge/repo-Kevin--RB%2Flocal--receipt-2ea44f?style=flat-square)](https://github.com/Kevin-RB/local-receipt)

### 🕸️ [crdc-workflows](https://github.com/Kevin-RB/crdc-workflows)

**Mastra pipelines that turn documents into knowledge graphs.** A four-stage workflow — chunking, entity extraction, relation extraction, Neo4j ingest — producing a queryable entity-relation graph. Every stage persists its state to disk, so a failed chunk reruns without redoing the corpus. Runs against local LLMs, with a chat agent and supervisor agent on top.

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
