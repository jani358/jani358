<h1 align="center">Janindu Gayanga</h1>
<p align="center"><b>Software Engineer</b> · Node.js · TypeScript · Go · React/Next.js · Distributed systems · AI agents</p>

<p align="center">
  <a href="https://iamjanindu.com"><img src="https://img.shields.io/badge/Portfolio-iamjanindu.com-1F6FEB?style=flat-square" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/janindu-gayanga-02ba60217"><img src="https://img.shields.io/badge/LinkedIn-janindu--gayanga-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:janindugayanga10@gmail.com"><img src="https://img.shields.io/badge/Email-janindugayanga10%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open%20to-On--site%20%C2%B7%20Hybrid%20%C2%B7%20Remote-2EA043?style=flat-square" alt="Open to on-site, hybrid or remote roles" />
</p>

I mostly build backend systems that have to stay **correct under concurrency**. A wallet can't credit twice, a queue can't give two people the same number, and a booking site can't sell one slot twice.

- Day job, 3+ years as a full-stack engineer: a real-money iGaming platform we're moving off a Node.js/MongoDB monolith onto **20 Go services + an API gateway**, with Kafka, PostgreSQL and Redis. 12,299 users and 584K records are migrating, and it ships with GitHub Actions and ArgoCD on K3s/AWS.
- After hours I build full products with ADRs, SLOs, a runbook, a postmortem and CI. That's where I learn the most.
- I use Claude Code and Cursor every day. Their code gets reviewed like anyone else's.

## Projects

| Project | What it shows | Stack |
|---|---|---|
| [**AskLK**](https://github.com/jani358/asklk-AI-assistant-showcase) | Multi-tenant Sinhala/English RAG with a tool-calling agent, an MCP server and a 46-case eval set gating PRs. Tenants are isolated by Postgres row-level security, with OIDC SSO. AWS Terraform verified on LocalStack. Full source on request. | NestJS · Next.js 15 · pgvector · OpenTelemetry |
| [**BookLK**](https://github.com/jani358/BookLK-showcase) | Booking marketplace: Kafka transactional outbox, Stripe/PayHere behind a payment port, GraphQL with DataLoader, Helm + ArgoCD on k3d, PACT contracts, and k6 at 500 virtual users with zero double bookings. Full source on request. | NestJS · Go · Kafka · MongoDB · Kubernetes |
| [**CallDocz (Nexora)**](https://github.com/jani358/nexora-callcenter-showcase) | Call-centre logging and reporting: schema-driven forms stored as JSONB with server-side validation, Postgres full-text search, idempotent saves and three roles. Architecture write-up; full source on request. | NestJS · Next.js · PostgreSQL · Prisma · Redis |
| [**QueueLK**](https://github.com/jani358/queuelk-showcase) | Real-time clinic queue with gap-free tokens under concurrency, Socket.io, Web Push and a React Native (Expo) app. k6 caught a connection-pool problem under load (p95 7.6 s); after fixing it and narrowing row locks, take-number p95 is 71–91 ms. BigQuery analytics export verified on emulators. Full source on request. | NestJS · Postgres · Redis · Expo · GCP |
| [**ApplyWise**](https://github.com/jani358/applywise-showcase) | AI job copilot. Every tailored CV line must cite a profile fact, and a CI eval gate fails at 1% fabrication (0.0% of 570 claims, measured on an offline test model). Includes a Go ATS parser and a Chrome extension. Full source on request. | Next.js 15 · NestJS · Go · pgvector · BullMQ |


## Toolbox

- **Languages:** TypeScript · JavaScript · Go · SQL
- **Backend:** Node.js · NestJS · Express · REST · GraphQL · WebSockets · Socket.io · SSE · Kafka · BullMQ
- **Frontend:** React · Next.js · React Native (Expo) · Redux Toolkit · Zustand · TanStack Query · Tailwind · shadcn/ui · MUI
- **AI:** LLMs (Claude, Gemini, OpenAI-compatible) · RAG · AI agents and tool calling · MCP · LLM evals in CI
- **Data:** PostgreSQL (RLS, pgvector) · MongoDB · Redis · BigQuery
- **Cloud and ops:** AWS · GCP · Docker · Kubernetes · Helm · ArgoCD · Terraform · GitHub Actions · OpenTelemetry · Prometheus · Grafana · Sentry
- **Testing:** Jest · Vitest · Playwright · Testcontainers · PACT · k6

## How I work

- I write the decision down before the code. Every repo has ADRs in `docs/adr/`.
- If I claim something about concurrency, there's a race test for it. My k6 reports keep the targets I missed, and AI output has to pass an eval gate.
- When something only ran on LocalStack, emulators or k3d, the README says so. I don't pretend it's on real AWS.

<p align="center"><sub>Colombo, Sri Lanka · open to Software Engineer / Senior Software Engineer roles: on-site, hybrid or remote</sub></p>
