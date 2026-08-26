<div align="center">

# Le Marc

**Staff Engineer · Full-stack · High-load systems**

*Complex problems, boring infrastructure, zero tolerance for demo-ware*

<br/>

[![GitLab](https://img.shields.io/badge/Home-GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/lemarco)
[![Rust](https://img.shields.io/badge/Evangelist-Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org)
[![Bun](https://img.shields.io/badge/Evangelist-Bun-000000?style=for-the-badge&logo=bun&logoColor=white)](https://bun.sh)

</div>

---

## About

**10 years** as Staff / Lead Engineer — from C++ financial data hammers to distributed systems at scale.

I build **high-load applications** with large datasets. Fintech, iGaming, B2B, B2C — domains where downtime costs money and "we'll fix it in the next sprint" isn't an option.

I don't just write code — I **design processes** that let teams ship faster without setting prod on fire.

I deliver to **production quickly** — and not just me personally. The people around me do too. That's the actual Staff Engineer job: remove blockers, shorten feedback loops, align the team on how to ship safely, and make sure deploying isn't a ceremony that requires one person's blessing.

---

## How I think about architecture

**Clean architecture** isn't a slide deck — it's how you keep a codebase alive when the team grows, the domain shifts, and someone new has to change prod on day three.

Domain logic stays domain logic. Infrastructure stays at the edges. Dependencies point inward. Not because Uncle Bob said so — because I've seen what happens when they don't.

Hexagonal, ports & adapters, bounded contexts — pick the vocabulary, the idea is the same: **make the hard parts testable and the easy parts replaceable**.

---

## How I think about AI

Most "AI products" are demos wearing a production badge. I don't do that.

I treat agents and workflows as **systems engineering** — same rules as any other service:

- clear boundaries and failure modes
- observability when the model goes off-script
- composable workflows, not prompt spaghetti
- integration into existing infra, not a parallel universe

The model is one component. The architecture around it is the job.

---

## How I think about infrastructure

I've worked with **`AWS`** — EC2, S3, RDS, the full managed stack. And **`Cloudflare`** — DNS, CDN, Workers, edge routing. Can ship on both, no problem.

But for the core workload, I prefer **bare metal**: you know exactly what you pay for, no abstraction tax when every millisecond counts, no surprise bill because someone left an RDS instance running since 2019. Cloudflare at the edge + bare metal behind it is a combo that actually makes sense.

**Cost efficiency** isn't being cheap — it's paying for capacity you actually use, picking the right tool for the workload, and not renting convenience when a well-tuned self-hosted stack does the job better.

---

## Stack

Ten years across the stack — from bare metal to browser, from batch pipelines to real-time event systems.

### Languages & Runtimes

`Rust` · `TypeScript` · `JavaScript` · `C++` · `Haskell` · `Elixir` · `Bun` · `Node.js` · `Cargo` · `Nix`

### Backend & APIs

`Axum` · `Tokio` · `NestJS` · `GraphQL` · `gRPC` · `REST`

microservices · event-driven · CQRS · contract-first APIs

### Frontend

`React` · `SolidJS` · `Svelte` · `Next.js`

SSR · component libraries · design systems

### Data & Storage

`PostgreSQL` · `MySQL` · `MongoDB` · `ClickHouse` · `Redis`

migrations · indexing · query optimization · analytics workloads

### Messaging & Streaming

`Kafka` · `RabbitMQ` · `NATS`

pub/sub · job queues · stream processing · async pipelines

### Platform & Ops

`AWS` · `Cloudflare` · `Kubernetes` · `Docker` · `Linux` · `GitLab CI`

bare metal · cost efficiency · right-sizing · CI/CD · observability · load balancing · caching · high availability · zero-downtime deploys · capacity planning

### Architecture

clean / hexagonal · DDD · ports & adapters · bounded contexts · monorepos · domain-centric design

### AI & Automation

LLM integration · agent workflows · tool orchestration · RAG pipelines · prompt pipelines as code · eval & observability

---

<div align="center">

**GitHub is a signpost → [github.com/lemarco](https://github.com/lemarco)**

*All repos live here. All commits happen here.*

</div>
