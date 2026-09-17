<div align="center">

# Ihor Hoienko

*Also **Le Marc** (`lemarco`) on [GitLab](https://gitlab.com/lemarco) & [crates.io](https://crates.io/users/lemarco)*

**Staff Engineer · ship fast, multiply the team**

*Rust · TypeScript · high-load · event pipelines · agents in production*

<br/>

[![GitLab](https://img.shields.io/badge/Home-GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/lemarco)
[![Rust](https://img.shields.io/badge/Evangelist-Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org)
[![Bun](https://img.shields.io/badge/Evangelist-Bun-000000?style=for-the-badge&logo=bun&logoColor=white)](https://bun.sh)

</div>

---

**Home → [gitlab.com/lemarco](https://gitlab.com/lemarco)** · [GitHub](https://github.com/lemarco) mirrors this profile

---

## Featured projects

### [**trembita**](https://gitlab.com/lemarco/trembita)

**A distributed Raft runtime for Rust** — one codebase, N nodes, elastic and self-healing. Published on [crates.io](https://crates.io/crates/trembita).

Embed consensus in your binary: same artifact on every node, HTTP/3/mTLS cluster, linearizable state machine, and a **capability platform** — typed ops (`#[cap_handler]`), jobs, event topics, workflows, real-time sessions — on embedded **redb** (library-first on VPS, no mandatory Redis). Multi-Raft write scaling, cross-shard sagas, rolling self-update. No sidecar, no control plane.

`Raft` · `Multi-Raft` · `HTTP/3` · `QUIC` · `mTLS` · `capabilities` · `redb` · 45 ADRs · Docker e2e · chaos tests

[![trembita on GitLab](https://img.shields.io/badge/trembita-GitLab-FC6D26?style=flat-square&logo=gitlab)](https://gitlab.com/lemarco/trembita)
[![crates.io](https://img.shields.io/crates/v/trembita?style=flat-square&logo=rust)](https://crates.io/crates/trembita)
[![docs.rs](https://img.shields.io/docsrs/trembita?style=flat-square&logo=docs.rs)](https://docs.rs/trembita)

### [**tilt**](https://gitlab.com/lemarco/tilt)

**Native Rust Wayland compositor** — i3/Sway-compatible tiling WM on [Smithay](https://github.com/Smithay/smithay). Active development.

Same config mental model as Sway (`bindsym`, workspaces, gaps), Sway-compatible IPC (`tilt msg`, waybar), XWayland, layer-shell — compositor logic in memory-safe Rust. Nested winit backend for dev; DRM/KMS path in progress.

`Wayland` · `Smithay` · `i3/Sway config` · `IPC` · `XWayland` · `layout tree`

[![tilt on GitLab](https://img.shields.io/badge/tilt-GitLab-FC6D26?style=flat-square&logo=gitlab)](https://gitlab.com/lemarco/tilt)

---

## Who

**10 years** as Staff / Lead Engineer on **high-load, data-heavy** platforms — fintech, iGaming, B2B, B2C. Work where **throughput and correctness both matter**: transactional paths under real traffic, analytics that must stay honest, and releases that cannot be a one-person ritual.

**Scale I've shipped:** event volumes in the **hundreds of millions per day** on individual hot streams (gaming telemetry was one slice of a much wider API surface). **Kafka** for ingestion and fan-out, **Debezium** CDC when OLTP stayed in Postgres/MySQL but reporting couldn't, **ClickHouse** for rollups, dashboards, and operator-facing aggregates — OLTP and OLAP kept separate on purpose.

**Staff scope:** mostly **product teams** (~**4–10 engineers**), plus **platform** stints. As Staff I've been the **single technical anchor across multiple squads** — architecture, unblocking, and shared standards when no one else owns the horizontal slice.

**What I change in orgs:** **architecture** that holds up under traffic and team churn; **CI/CD and DX** (pipelines, conventions, less release friction); **ADR-style** decision records where they pay off. Introduced **practical AI in engineering workflows** and an internal **harness** (profiles, rules, repo conformance) so teams don't reinvent process every sprint.

I ship to **production quickly** — and the people around me do too.

---

## How I think about architecture

**Clean architecture** keeps a codebase alive when the team grows and someone new touches prod on day three. Domain logic stays domain logic, infrastructure at the edges, dependencies point inward — **hard parts testable, easy parts replaceable**.

---

## How I think about AI

Agents and workflows are **systems engineering**, not demos. Clear boundaries, observability when the model goes off-script, composable workflows, integration into existing infra. The model is one component — the architecture around it is the job.

**Currently focused on:** **trembita** (distributed runtime for product backends) and agent workflows / production RAG pipelines.

---

## How I think about infrastructure

**`AWS`** and **`Cloudflare`** — fine, I've shipped on both. For core workloads I prefer **bare metal**: known costs, no abstraction tax, no surprise bills. Edge on Cloudflare, compute on metal — that combo makes sense.

**Cost efficiency** means paying for capacity you use and picking the right tool — not renting managed services when a tuned self-hosted stack does it better.

---

## Stack

### Languages & Runtimes

`Rust` · `TypeScript` · `JavaScript` · `Bun` · `Node.js` · `Cargo`

Side projects & learning (not production-shipped): `C++` · `Haskell` · `Elixir` · `Nix`

### Backend & Frontend

`Axum` · `Tokio` · `NestJS` · `GraphQL` · `gRPC` · `REST` · `React` · `SolidJS` · `Svelte` · `Next.js`

microservices · event-driven · CQRS · SSR · design systems · contract-first APIs

### Data & Storage

`PostgreSQL` · `MySQL` · `MongoDB` · `ClickHouse` · `Redis`

OLTP vs OLAP split · migrations · indexing · columnar aggregates · reporting workloads

### Messaging & Streaming

`Kafka` · `Debezium` · `RabbitMQ` · `NATS`

CDC · pub/sub · job queues · stream processing · async pipelines

### Platform & Ops

`AWS` · `Cloudflare` · `Kubernetes` · `Docker` · `Linux` · `GitLab CI`

bare metal · cost efficiency · right-sizing · CI/CD · observability · high availability · zero-downtime deploys

---

<div align="center">

Open to staff / lead roles · Warsaw (CET) · remote-friendly · [lemarc.dev@gmail.com](mailto:lemarc.dev@gmail.com)

[![GitLab](https://img.shields.io/badge/GitLab-lemarco-FC6D26?style=flat-square&logo=gitlab)](https://gitlab.com/lemarco)
[![GitHub](https://img.shields.io/badge/GitHub-lemarco-181717?style=flat-square&logo=github)](https://github.com/lemarco)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ihor_Hoienko-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ihor-hoienko-2b444287/)

</div>
