<div align="center">

```
╭──────────────────────────────────────────────────────────────╮
│ ✻ Welcome to Viral's profile                                 │
│                                                              │
│   /help for help, /projects to see what I've shipped         │
│                                                              │
│   cwd: ~/ig-ViraL                                            │
╰──────────────────────────────────────────────────────────────╯
```

# Viral Deshle

**Senior Software Engineer · Team Lead · Full-Stack & GenAI**

Building real-time, scalable platforms, from WhatsApp-driven healthcare SaaS to retail systems running 170+ stores.<br/>
Surat, Gujarat, India · Open to remote and relocation

<a href="https://www.linkedin.com/in/viral-deshle/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:viraldeshle1234@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.viral-deshle.cloud/"><img src="https://img.shields.io/badge/Portfolio-d77757?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>
<a href="https://github.com/ig-ViraL"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

</div>

<br/>

## `> whoami`

```console
viral@surat:~$ cat profile.json
{
  "role":        "Sr. Software Engineer @ Webvoltz (Team Lead, team of 5)",
  "experience":  "3 years across startups, D2C and enterprise retail",
  "focus":       ["real-time systems", "distributed architecture", "GenAI full-stack"],
  "currently":   "Building RAG pipelines, LLM-integrated APIs and MCP tooling",
  "certified":   "AWS Certified Developer – Associate (888/1000)",
  "education":   "B.Tech CS, GTU (CGPA 9.17)",
  "principle":   "Impact-first, outcome-driven"
}
```

## `> impact --summary`

<div align="center">

| 🏬 **170+** | 📦 **800+** | 👥 **1M+** | 💬 **30M+** | 💸 **$6K/mo** |
|:---:|:---:|:---:|:---:|:---:|
| retail stores on one POS | daily orders processed | peak-event users, zero downtime | real-time messages handled | infra cost saved |

| ⚡ **45K** | 🚚 **-60%** | 🛒 **-40%** | 🗂️ **7M+** | 🤖 **10** |
|:---:|:---:|:---:|:---:|:---:|
| concurrent users on WebSockets | delivery failures | cart-to-order time | coupons indexed in DynamoDB | MCP tools shipped |

| 🏢 **6** | 🎟️ **15,000** | 🔁 **0** | 🔫 **35–95 ms** | 🧪 **420+** |
|:---:|:---:|:---:|:---:|:---:|
| Webvoltz case studies published | seats on one live map | double sends on duplicate webhooks | per CCTV frame on one GPU | tests across Webvoltz builds |

</div>

## `> experience`

### Sr. Software Engineer · [Webvoltz](https://webvoltz.com) · *Jun 2026 – Present*

**CarePath: Multi-tenant patient communication platform for dental clinics**
<sub>`Next.js` · `WhatsApp Business API` · `SMS` · `RBAC` · `Webhooks`</sub>

- Lead architecture and delivery of a multi-tenant SaaS automating clinic-to-patient communication over WhatsApp and SMS, with RBAC across 4 roles (Super Admin, Clinic Admin, Staff, Patient).
- Built a **dynamic workflow engine**: master workflows that clinics clone, with steps scheduled relative to patient-specific dates (e.g. surgery date ± N days) and **snapshotted at enrollment**, so template edits never break in-flight patient journeys.
- Integrated the WhatsApp Business API: Meta-approved templates, webhook-driven two-way chat gated by the **23-hour customer service window**, and automatic **SMS fallback** on delivery failure.
- Implemented **red-flag detection** on patient replies (English, Hindi, Gujarati and Roman-script keywords) that raises real-time staff alerts, backed by audit logs with delivery status.

**Webvoltz client work: published case studies**

| Case study | Outcome | Stack |
|:--|:--|:--|
| 🎟️ **[Event Seating Map](https://github.com/vish2293/event-seating-map-case-study)** | Live seat map for a **15,000-seat venue**: only the open section's 1,500 seats go live, so clicks paint in ~2 frames. Seat holds expire on time and no seat is ever shown to two buyers. 222 tests. | `React 19` `TypeScript` `Redis` `PostgreSQL` `WebSockets` |
| 🔁 **[CRM Automation](https://github.com/vish2293/crm-automation-case-study)** | GoHighLevel integration where **one front-desk click** runs a full review-request campaign. Eight send gates, a Postgres job queue with `SKIP LOCKED`, and webhooks applied **exactly once**. 141 tests. | `Node 22` `TypeScript` `PostgreSQL` `GoHighLevel API` |
| 📄 **[DocMind](https://github.com/vish2293/docmind-case-study)** | Agentic Q&A over long documents: structure-aware indexing, a bounded research agent, hybrid search reranking **50 → 5**, and a second model that removes any claim the evidence doesn't support. | `FastAPI` `pgvector` `Claude` `bge-reranker` |
| 🕸️ **[Websearch](https://github.com/vish2293/search-engine-case-study)** | AI search engine with its **own crawler and index** and no third-party search API. Adaptive crawling, hybrid keyword + semantic ranking, and answers that can't cite pages they didn't read. | `Scrapy` `OpenSearch` `PostgreSQL` `bge-m3` |
| 🔫 **[Netram](https://github.com/vish2293/netram-weapon-detection-case-study)** | Real-time person and gun detection on CCTV with two-pass YOLO and ByteTrack. **35–95 ms per frame** on one GPU, with distant weapons given 2.2× the pixels. | `YOLO` `ByteTrack` `PyTorch` `FastAPI` |
| 🗺️ **[Map Solutions Guide](https://github.com/vish2293/map-solutions-guide-case-study)** | Playbook for map products: drawn zones, data-driven styling, address search, point-in-zone lookups and distance APIs, drawn from a reference project with 1,350+ tests. | `Mapbox GL` `Turf.js` `PostGIS` |

**Team leadership & delivery**
- Team lead for **5 engineers**, owning projects from requirements to deployment across the full SDLC.
- Re-architected and delivered **3 existing projects** and onboarded **3 new ones** from the ground up.
- Own code review and PR approval; introduced **CodeRabbit** for AI-assisted reviews, catching bugs earlier and cutting manual review time.

---

### Full Stack Developer · [devx labs](https://devxlabs.ai) · *Dec 2024 – Feb 2026*

**The Sleep Company: Enterprise POS & retail platform**
<sub>`React` · `Next.js` · `GraphQL` · `AWS Lambda` · `ECS` · `API Gateway` · `DynamoDB` · `Cognito` · `Step Functions`</sub>

- Led delivery of a POS platform across **170+ stores** processing **800+ daily orders**.
- Revamped the checkout flow, cutting cart-to-order completion time by **40%**.
- Architected an event-driven **Order Editing workflow on AWS Step Functions** with live recalculation, reducing CRM manual workload by **60%**.
- Integrated **6 payment gateways** (Razorpay, PayU, Snapmint, Pine Labs POS, Gyftr, cash) with Shopify GraphQL as the central OMS.
- Designed a DynamoDB indexing strategy tracking **7M+ coupons**, and replaced cron jobs with **EventBridge** scheduling, fixing observability gaps and environment drift across dev, UAT and prod.

**Foxtale: D2C e-commerce platform**
<sub>`Next.js` · `Strapi CMS` · `Shopify OMS` · `AWS ECS Fargate`</sub>

- Served **100K+ DAU** and scaled to **1M+ users and 10K+ orders/day** during peak sales with **zero downtime**.
- Built homepage personalization by location and segment, with Next.js **ISR** for fast, always-fresh pages.
- Replaced CloudFront with a custom Shopify CDN Strapi plugin, saving **$6,000/month**.
- Cut delivery failures by **60%** with Google Maps geolocation and address normalization.
- Integrated **8+ third-party services** (Gupshup, Mixpanel, WebEngage, GTM, ClickPost, EasyEcom).

**Reliability & leadership:** API Gateway rate limiting, SSM/Secrets Manager, CloudWatch; primary on-call for production incidents; mentored 3 developers; ran system design and DSA interviews; led the Next.js 15 → 16 migration; authored architecture docs.

---

### Jr. Full Stack Developer · WebOsmotic · *Feb 2023 – Nov 2024*

- Built a real-time communication platform (chat, Q&A, presence) for **45K concurrent / 240K unique users** and **30M+ messages**, on `Node.js` · `Socket.IO` · `Redis pub/sub` for horizontal scaling.
- Developed **Narad.io**, a notification module delivering system and user events with **sub-second latency**.
- Built **Guidy**, a WCAG accessibility platform: Puppeteer-based auditing API, a nightly Lambda re-crawl, and 3 embeddable widgets.
- Prototyped **WebRTC** P2P video and stress-tested dashboards against simulated millions of concurrent WebSocket connections.

## `> ls projects/`

| Project | What it does | Stack |
|:--|:--|:--|
| **DocMind** · RAG Document Q&A · [UI](https://www.viral-deshle.cloud/docmind) · [Code](https://github.com/ig-ViraL/doc-mind-backend) | End-to-end RAG: PDF/DOCX/TXT ingestion, recursive chunking, MiniLM embeddings, pgvector IVFFlat, cross-encoder reranking, hybrid search (pgvector + BM25 via RRF), Claude synthesis with citations, streamed over SSE. | `Python` `FastAPI` `pgvector` `Claude API` `Next.js` `Docker` |
| **PostgreSQL MCP Server** · [Live demo](https://www.viral-deshle.cloud/pg-mcp) · [Code](https://github.com/ig-ViraL/pg-mcp-server) | Production MCP server exposing **10 tools** (schema discovery, query execution, performance analysis, DB health). Sandboxed: read-only role, mutation blocking, auto `LIMIT`, 5s timeout, AES-256-GCM encrypted connection strings, zero server-side credentials. | `Python` `FastMCP` `asyncpg` `React` `Railway` |
| **Real-Time Stock Screener** · [Live demo](https://stock-screener-beta-two.vercel.app/) · [Code](https://github.com/ig-ViraL/stock-screener) | Live dashboard streaming 25+ stocks over Finnhub WebSocket. `use cache` + Partial Prerendering for a **90%+ cache hit rate** within API rate caps; URL-driven, shareable filters. | `Next.js 16` `TypeScript` `WebSockets` |

> The PG-MCP demo is live; the DocMind backend runs on free-tier hosting and is offline between demos, so its repo includes Docker setup to run it locally. More on my [portfolio](https://www.viral-deshle.cloud/). Also public: [claude-code agents](https://github.com/ig-ViraL/agents) and [DSA practice](https://github.com/ig-ViraL/DSA). Built with Claude Code as a pair programmer; the architecture and decisions are mine.

## `> cat skills.txt`

<div align="center">

| | |
|:--|:--|
| **Languages** | `JavaScript` `TypeScript` `Python` `SQL` |
| **Frontend** | `React` `Next.js` `Tailwind CSS` `WCAG Accessibility` |
| **Backend** | `Node.js` `Express` `NestJS` `FastAPI` `GraphQL` `REST` `WebSockets` `WebRTC` |
| **Data** | `PostgreSQL` `MongoDB` `DynamoDB` `Redis` `Elasticsearch` `OpenSearch` `pgvector` |
| **Cloud & DevOps** | `AWS` `Docker` `Terraform` `GitHub Actions` `Vercel` `CI/CD` |
| **Architecture** | `Microservices` `Event-Driven` `Distributed Systems` `System Design` |
| **AI & GenAI** | `RAG` `Vector Search` `Embeddings` `Agents` `LLM Integration` `MCP` `FastMCP` `Computer Vision` |
| **Integrations** | `WhatsApp Business API` `GoHighLevel` `Shopify` `Payment Gateways` |
| **Workflow** | `Claude Code` `Cursor` `CodeRabbit` `Git` `Jira` `Agile/Scrum` |

<img src="https://skillicons.dev/icons?i=ts,js,py,react,nextjs,tailwind,nodejs,nestjs,fastapi,graphql,postgres,mongodb,redis,dynamodb,aws,docker,terraform,githubactions&perline=9" />

</div>

## `> git log --stat`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=ig-ViraL&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ig-ViraL&layout=compact&theme=tokyonight&hide_border=true" height="165"/>

<img src="https://streak-stats.demolab.com?user=ig-ViraL&theme=tokyonight&hide_border=true" />

</div>

## `> credentials`

- 🏆 **AWS Certified Developer – Associate**, Feb 2026, score **888/1000**
- 🎓 **B.Tech in Computer Science**, Gujarat Technological University, 2019–2023, CGPA **9.17**

## `> contact --open`

I'm open to senior and lead full-stack roles, especially around real-time systems, distributed architecture and GenAI products.

```console
viral@surat:~$ echo "Let's build something that scales."
Let's build something that scales.
```

<div align="center">
<sub>✻ Engineered with care · Updated October 2026</sub>
</div>
