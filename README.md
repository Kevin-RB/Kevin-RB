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

I love building things that actually work, especially when software engineering meets AI. I recently completed a **Master of Information Technology (MIT) in Australia** (super proud of it btw 🦘).

My focus is building systems and products that deliver actual value. I care about making things genuinely useful to the person using them, and a pleasure to use.

What draws me in is the machinery underneath: system design, architecture, and how a product behaves under real use and real load. I like the whole stack, form data models, durable workflows, auth, storage, realtime, to deployment, and thinking about how the pieces interact and where the system fails.

AI is a tool I reach for when it's genuinely the right tool for a problem, not the premise I'm starting from.

Most of my projects are things I designed, built, and shipped end to end rather than inherited from a spec.

## <a name="projects"></a>Featured Projects

### 📸 [local-receipt](https://github.com/Kevin-RB/local-receipt)

**Local-first receipt AI analyser.** Photograph a receipt and it becomes structured, persistent data, merchant, line items, totals, GST, and date are extracted by local vision models and stored with the original image. Durable background jobs, live progress updates, and integrity warnings when line items don't sum to the stated total.

**Stack:** Next.js 16 (App Router) · React 19 · TypeScript · Tailwind CSS 4 · shadcn/ui · Drizzle ORM · Postgres · RustFS (S3-compatible) · Inngest (durable jobs + realtime) · AI SDK · Better Auth · Docker Compose · Vitest

[![live · invite only](https://img.shields.io/badge/live%20%C2%B7%20invite%20only-2ea44f?style=flat-square&logo=googlechrome&logoColor=white)](https://receipts.tribi.dev) — [reach out to me](https://www.linkedin.com/in/kevinromerob/) if you'd like access

[![local-receipt](https://img.shields.io/badge/repo-Kevin--RB%2Flocal--receipt-2ea44f?style=flat-square)](https://github.com/Kevin-RB/local-receipt)

### 🕸️ [crdc-workflows](https://github.com/Kevin-RB/crdc-workflows)

**Mastra pipelines that turn documents into knowledge graphs.** A four-stage workflow: chunking, entity extraction, relation extraction, Neo4j ingest, producing a queryable entity-relation graph. Every stage persists its state to disk, so a failed chunk reruns without redoing the corpus. Runs against local LLMs, with a chat agent and supervisor agent on top.

**Stack:** TypeScript · Mastra (agents, workflows, RAG, memory, evals) · Neo4j · DuckDB / libSQL · Zod · LM Studio (local OpenAI-compatible LLM) · Docker · pnpm

[![crdc-workflows](https://img.shields.io/badge/repo-Kevin--RB%2Fcrdc--workflows-2ea44f?style=flat-square)](https://github.com/Kevin-RB/crdc-workflows)

## <a name="stack"></a>Stack

**Languages**
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript) [![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org) [![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/docs/current/sql.html)

**Frontend**
[![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)](https://react.dev) [![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org) [![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com) [![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)](https://ui.shadcn.com)

**Backend**
[![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org) [![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black)](https://orm.drizzle.team) [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org) [![Better Auth](https://img.shields.io/badge/Better_Auth-000000?style=flat-square&logo=betterauth&logoColor=white)](https://better-auth.com)

**AI & Agents**
[![Mastra](https://img.shields.io/badge/Mastra-6E56CF?style=flat-square)](https://mastra.ai) [![Vercel AI SDK](https://img.shields.io/badge/AI_SDK-000000?style=flat-square&logo=vercel&logoColor=white)](https://ai-sdk.dev) [![Inngest](https://img.shields.io/badge/Inngest-000000?style=flat-square)](https://www.inngest.com) [![LM Studio](https://img.shields.io/badge/LM_Studio-10A37F?style=flat-square&logo=lmstudio&logoColor=white)](https://lmstudio.ai) [![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white)](https://neo4j.com) [![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)](https://duckdb.org)

**Infrastructure**
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com) [![Coolify](https://img.shields.io/badge/Coolify-6D5AE8?style=flat-square&logo=coolify&logoColor=white)](https://coolify.io) [![Amazon S3](https://img.shields.io/badge/S3-FF9900?style=flat-square)](https://aws.amazon.com/s3/) [![RustFS](https://img.shields.io/badge/RustFS-B7410E?style=flat-square)](https://rustfs.com)

**Tooling**
[![pnpm](https://img.shields.io/badge/pnpm-F69220?style=flat-square&logo=pnpm&logoColor=white)](https://pnpm.io) [![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)](https://vitest.dev) [![Biome](https://img.shields.io/badge/Biome-60A5FA?style=flat-square&logo=biome&logoColor=white)](https://biomejs.dev) [![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions)

## <a name="connect"></a>Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kevinromerob/)
