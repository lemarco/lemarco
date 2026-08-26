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

## Stack

<table>
<tr>
<td valign="top" width="50%">

**Languages & Runtimes**

`Rust` · `TypeScript` · `Haskell` · `Elixir` · `C++`

**Backend**

`Axum` · `NestJS` · Microservices · Event-driven

**Frontend**

`React` · `SolidJS` · `Svelte`

</td>
<td valign="top" width="50%">

**Data & Messaging**

`PostgreSQL` · `MySQL` · `MongoDB` · `ClickHouse`

`Kafka` · `RabbitMQ` · `NATS`

**Infra & Ops**

High-load architecture · Process design · Team leadership

</td>
</tr>
</table>

---

## The path here

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#1a1a2e', 'primaryTextColor': '#e0e0e0', 'primaryBorderColor': '#6366f1', 'lineColor': '#6366f1', 'secondaryColor': '#16213e', 'tertiaryColor': '#0f3460'}}}%%
flowchart LR
    A["<b>C++ era</b><br/>financial data pipelines<br/><i>low-level grit</i>"]
    B["<b>Startup era</b><br/>full-stack chaos<br/><i>B2B · B2C products</i>"]
    C["<b>Scale era</b><br/>fintech · iGaming<br/><i>high-load · big data</i>"]
    D["<b>Now</b><br/>Staff Engineer<br/><i>clean arch · agents in prod</i>"]

    A --> B --> C --> D

    style A fill:#1e1e2e,stroke:#6366f1,stroke-width:2px,color:#e0e0e0
    style B fill:#1e1e2e,stroke:#818cf8,stroke-width:2px,color:#e0e0e0
    style C fill:#1e1e2e,stroke:#a78bfa,stroke-width:2px,color:#e0e0e0
    style D fill:#312e81,stroke:#c4b5fd,stroke-width:2px,color:#f0f0f0
```

---

<div align="center">

**GitHub is a signpost → [github.com/lemarco](https://github.com/lemarco)**

*All repos live here. All commits happen here.*

</div>
