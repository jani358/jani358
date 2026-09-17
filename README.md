<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:1F6FEB,100:8957E5&height=200&section=header&text=Janindu%20Gayanga&fontSize=52&fontColor=FFFFFF&fontAlignY=35&desc=Senior%20Software%20Engineer%20%E2%80%A2%20Go%20%E2%80%A2%20Distributed%20Systems%20%E2%80%A2%20AI&descAlignY=58&descSize=18" width="100%" />

<a href="https://iamjanindu.com/"><img src="https://img.shields.io/badge/Portfolio-1F6FEB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/janindu-gayanga-02ba60217/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:janindugayanga10@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://komarev.com/ghpvc/?username=jani358&style=for-the-badge&color=8957E5&label=PROFILE+VIEWS" alt="Profile views" />

</div>

---

## 👋 About me

Full-stack engineer from Colombo, Sri Lanka. I spend most of my time on **backend systems where
correctness under concurrency matters** — wallets that must never double-credit, queues that must
never hand two people the same number, bookings that must never sell one slot twice.

```text
Production  ·  Go · TypeScript · NestJS · Next.js · PostgreSQL · Redis · Kafka
Scale       ·  10,000+ concurrent WebSocket connections at sub-100 ms
Migration   ·  Led a Node.js → Go move of the hot paths after profiling proved it was CPU-bound
Infra       ·  Docker · Kubernetes (K3s) · Terraform · ArgoCD GitOps · AWS
Right now   ·  Bilingual RAG (pgvector, hybrid retrieval) and real-time SaaS for Sri Lankan businesses
```

---

## 🧩 What I build

<table>
<tr>
<td width="33%" valign="top">

### 🤖 AskLK
**Bilingual AI assistant**

Ask in Sinhala, get Sinhala — from an English document. Multi-tenant RAG on **pgvector**, hybrid
retrieval (vector + full-text merged by **Reciprocal Rank Fusion**) in one SQL query, four
anti-hallucination layers, SSE streaming, 14 KB embeddable widget.

`NestJS` `pgvector` `Next.js` `Gemini`

[**→ Read the write-ups**](https://github.com/jani358/asklk-AI-assistant-showcase)

</td>
<td width="33%" valign="top">

### 🎫 QueueLK
**Real-time queue & tokens**

Take a number from your phone, watch the counter from the waiting room. Gap-free numbering under
concurrency (`SELECT … FOR UPDATE` plus a unique-constraint backstop), live SSE display boards,
multi-tenant SaaS for clinics and counters.

`NestJS` `PostgreSQL` `SSE` `Redis`

[**→ Read the write-ups**](https://github.com/jani358/queuelk-showcase)

</td>
<td width="33%" valign="top">

### 📅 BookLK
**Booking marketplace**

Double-booking is a correctness problem, not a UI problem. Idempotency keys, Redis locks and a row
lock inside a serializable transaction — with a concurrent test that asserts exactly one winner.

`Next.js` `NestJS` `Go` `PostgreSQL`

[**→ Read the write-ups**](https://github.com/jani358/BookLK-showcase)

</td>
</tr>
</table>

### Also, at work and on my own time

| | |
|---|---|
| **iGaming platform** (production) | 18 Go microservices behind an API gateway · Kafka events · the wallet/ledger service where four independent layers stop a player being double-credited · 10,000+ live WebSocket connections |
| **Infrastructure** | Terraform-provisioned AWS → K3s + ArgoCD GitOps · Prometheus, Grafana, Loki, Tempo · a dev environment that costs tens of dollars instead of ~$1,000/month managed |
| **Go trading bot** | Binance futures, indicators computed in Go, an LLM as the *proposal* and ~15 deterministic risk gates as the *decision* — each gate added after a real losing trade |
| **Retail POS** (Electron) | Offline-first desktop point of sale · integer-cent money in a shared module · verified backups after every bill |

---

## 🛠️ Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=go,ts,js,c&theme=dark" />

**Backend & data**

<img src="https://skillicons.dev/icons?i=nestjs,nodejs,postgres,redis,kafka,prisma,mongodb&theme=dark" />

**Frontend**

<img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,electron&theme=dark" />

**Infrastructure**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,terraform,aws,githubactions,grafana,linux&theme=dark" />

</div>

---

## 📊 GitHub

<div align="center">

<img src="https://github-trophies.vercel.app/?username=jani358&theme=discord&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" alt="Trophies" />

<br />

<img height="165" src="https://janindu-stats.vercel.app/api?username=jani358&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=1F6FEB&icon_color=8957E5" alt="Stats" />
<img height="165" src="https://streak-stats.demolab.com/?user=jani358&hide_border=true&theme=tokyonight&background=0D1117&ring=1F6FEB&fire=8957E5&currStreakLabel=8957E5" alt="Streak" />

<br />

<img height="165" src="https://janindu-stats.vercel.app/api/top-langs/?username=jani358&layout=compact&langs_count=8&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=1F6FEB" alt="Top languages" />

<br /><br />

<img src="https://ghchart.rshah.org/1F6FEB/jani358" alt="Contribution graph" width="96%" />

</div>

---

<div align="center">

### 💬 Open to senior backend, platform and AI-engineering roles

<a href="mailto:janindugayanga10@gmail.com"><img src="https://img.shields.io/badge/Let's%20talk-janindugayanga10@gmail.com-1F6FEB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8957E5,50:1F6FEB,100:0D1117&height=120&section=footer" width="100%" />

</div>
