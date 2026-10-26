<!--
  SANJAY KOLLIMARLA — ENGINEERING PROFILE
  Theme: Midnight / Cyan / Violet
  Replace the LinkedIn and project URL placeholders before publishing.
-->

<div align="center">


<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0F172A,50:164E63,100:7C3AED&text=SANJAY%20KOLLIMARLA&fontSize=38&fontColor=67E8F9&fontAlignY=40&animation=fadeIn" width="100%" alt="Sanjay Kollimarla"/>
</p>


<a href="https://readme-typing-svg.demolab.com">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&duration=2800&pause=900&color=67E8F9&center=true&vCenter=true&width=850&lines=Designing+Reliable+Backend+Systems;Engineering+Distributed+Processing+Pipelines;Node.js+%7C+TypeScript+%7C+Redis+%7C+MongoDB;Turning+Complex+Problems+Into+Maintainable+Systems" alt="Animated engineering tagline"/>
</a>

<br/>

<a href="https://sanjay-kollimarla.vercel.app/">
<img src="https://img.shields.io/badge/PORTFOLIO-Visit%20Website-0F172A?style=for-the-badge&logo=vercel&logoColor=67E8F9" alt="Portfolio"/>
</a>
<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/LINKEDIN-Connect-0F172A?style=for-the-badge&logo=linkedin&logoColor=67E8F9" alt="LinkedIn"/>
</a>
<a href="https://github.com/sanjay-kollimarla?tab=repositories">
<img src="https://img.shields.io/badge/REPOSITORIES-Explore-0F172A?style=for-the-badge&logo=github&logoColor=67E8F9" alt="Repositories"/>
</a>

</div>

---

## `$ whoami`

I'm **Sanjay Kollimarla**, a software engineer with 3+ years of experience building web applications and backend services.

My current engineering focus is on the intersection of **backend architecture, distributed systems, asynchronous processing, and performance engineering**.

I enjoy understanding what happens beyond a successful API response: how work moves through queues, how concurrent operations remain correct, how caching changes system behavior, how failures propagate, and how software can recover predictably.

I approach engineering with a simple principle:

> Build systems that remain understandable, measurable, and reliable as complexity grows.

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Engineering Focus

- Distributed backend services
- Reliable asynchronous processing
- API design and authorization
- Database performance and caching
- Concurrency and failure recovery
- System design and scalability

</td>
<td width="50%" valign="top">

### 🧭 Current Technology Stack

- **Runtime:** Node.js, Bun
- **Language:** TypeScript, JavaScript
- **Frameworks:** Express.js, Hono
- **Data:** MongoDB, Redis, MySQL
- **Infrastructure:** AWS, Docker, Kubernetes
- **Processing:** BullMQ, Redis-backed workers

</td>
</tr>
</table>

---

## `01 / ENGINEERING CAPABILITIES`

<table>
<tr>
<td width="50%" valign="top">

### ◈ Backend Architecture

Designing modular services, REST APIs, middleware, authorization boundaries, and maintainable application layers.

### ◈ Distributed Processing

Exploring queues, worker concurrency, retries, backoff, idempotency, dead-letter handling, and controlled job execution.

### ◈ Data & Performance

Using indexing, query optimization, caching, aggregation pipelines, and workload-driven performance analysis.

</td>
<td width="50%" valign="top">

### ◈ Reliability Engineering

Thinking through partial failures, duplicate delivery, timeout handling, recovery strategies, and operational visibility.

### ◈ Real-Time Systems

Building event-driven workflows with WebSockets, Server-Sent Events, and webhooks.

### ◈ Cloud & Delivery

Working with containerized applications, object storage, CI/CD workflows, and cloud deployment concepts.

</td>
</tr>
</table>

---

## `02 / SELECTED ENGINEERING PROJECTS`

### `01` — Distributed Email Queue Platform

**Reliable asynchronous processing | BullMQ + Redis**

A distributed job-processing platform designed around controlled execution, failure recovery, and worker scalability.

**Core engineering areas**

- Retry policies with exponential backoff
- Dead-letter queues and failed-job inspection
- Idempotent processing and duplicate-execution protection
- Worker concurrency and priority-based processing
- Rate limiting and controlled job throughput
- Job lifecycle tracking through SSE and webhooks
- Docker-based local development and integration testing

**Architecture to document**

`API → Queue → Redis → Workers → Processing → Status Events`

The key design challenge is not simply putting work in a queue. It is defining what happens when jobs fail, workers restart, requests are duplicated, or downstream services become unavailable.

**Stack:** `Node.js` `TypeScript` `BullMQ` `Redis` `Docker`

[**↗ VIEW SOURCE CODE**](YOUR_EMAIL_QUEUE_REPO_URL)

---

### `02` — Distributed Rate Limiting Service

**Coordinated request control | Redis + Lua**

A reusable rate-limiting service designed to enforce request policies across multiple application instances using shared state.

**Core engineering areas**

- Token Bucket and Sliding Window algorithms
- Atomic Redis operations and Lua scripts
- Per-client limits and configurable policies
- Express middleware integration
- Boundary conditions and concurrent request handling
- Expiration, cleanup, and failure behavior
- Reproducible throughput and latency benchmarks

**Architecture to document**

`Client → Middleware → Policy Evaluation → Redis Atomic Operation → Allow / Reject`

The central engineering question is how to enforce consistent rate limits when multiple application instances process requests simultaneously.

**Stack:** `Node.js` `TypeScript` `Redis` `Lua` `Express`

[**↗ VIEW SOURCE CODE**](YOUR_RATE_LIMITER_REPO_URL)

---

### `03` — Distributed URL Shortening Service

**Low-latency redirects | MongoDB + Redis**

A URL-shortening backend exploring efficient identifier generation, redirect handling, cache behavior, and asynchronous analytics.

**Core engineering areas**

- Short-code generation and collision handling
- URL persistence and expiration policies
- Redis caching for redirect lookups
- Cache consistency and invalidation
- Asynchronous click analytics
- Duplicate detection and link lifecycle management
- Performance measurement under representative workloads

**Architecture to document**

`Create Link → Generate Code → Persist → Cache → Redirect → Analytics`

The design focuses on separating the latency-sensitive redirect path from secondary analytics work while considering cache misses, expired links, and storage failures.

**Stack:** `Node.js` `TypeScript` `MongoDB` `Redis` `Docker` `AWS`

[**↗ VIEW SOURCE CODE**](YOUR_URL_SHORTENER_REPO_URL)

---

## `03 / TECHNOLOGY MATRIX`

<div align="center">

### Languages

<img src="https://skillicons.dev/icons?i=ts,js,java,python&theme=dark" alt="TypeScript JavaScript Java Python"/>

### Backend & Frameworks

<img src="https://skillicons.dev/icons?i=nodejs,express,bun&theme=dark" alt="Node.js Express Bun"/>

### Data & Messaging

<img src="https://skillicons.dev/icons?i=mongodb,mysql,redis&theme=dark" alt="MongoDB MySQL Redis"/>

### Cloud, Containers & Tooling

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,git,github,linux&theme=dark" alt="AWS Docker Kubernetes Git GitHub Linux"/>

</div>

**Additional concepts:** REST APIs · WebSockets · SSE · Webhooks · BullMQ · Lua scripting · RBAC · Multi-tenancy · Database indexing · Aggregation pipelines · Caching · CI/CD · Data Structures & Algorithms · System Design

---

## `04 / ENGINEERING PRINCIPLES`

| Principle | How I approach it |
|---|---|
| Correctness before optimization | Establish invariants and expected behavior before tuning performance. |
| Explicit failure handling | Define retry limits, timeouts, recovery behavior, and failure boundaries. |
| Concurrency awareness | Understand shared state, atomic operations, duplicate execution, and race conditions. |
| Measure before claiming | Use reproducible benchmarks and clearly document workload assumptions. |
| Design for maintainability | Separate responsibilities and make dependencies and contracts explicit. |
| Operational visibility | Use structured logs, metrics, traces, and meaningful error context where appropriate. |

---

## `05 / GITHUB ACTIVITY`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=sanjay-kollimarla&show_icons=true&hide_border=true&bg_color=080D1A&title_color=67E8F9&text_color=C9D1D9&icon_color=A78BFA&rank_icon=github&include_all_commits=true" height="165" alt="GitHub statistics"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjay-kollimarla&layout=compact&hide_border=true&bg_color=080D1A&title_color=67E8F9&text_color=C9D1D9" height="165" alt="Most-used languages"/>

<img src="https://streak-stats.demolab.com?user=sanjay-kollimarla&hide_border=true&background=080D1A&ring=67E8F9&fire=A78BFA&currStreakLabel=67E8F9&sideLabels=C9D1D9&dates=94A3B8&currStreakNum=FFFFFF&sideNums=FFFFFF" width="80%" alt="GitHub contribution streak"/>

</div>

---

## `06 / CONTRIBUTION GRAPH`

<div align="center">

<img src="https://raw.githubusercontent.com/sanjay-kollimarla/sanjay-kollimarla/output/github-snake-dark.svg" width="100%" alt="Animated contribution snake"/>

</div>

---

## `07 / WHAT I VALUE IN SOFTWARE`

```text
Readable code       > Clever code without clarity
Measured performance > Assumptions about speed
Explicit contracts  > Hidden dependencies
Reliable recovery   > Happy-path-only behavior
Useful abstractions > Unnecessary complexity
```

I'm interested in engineering teams that value strong technical fundamentals, thoughtful system design, ownership, code quality, and continuous improvement.

---

## `08 / CONNECT`

<div align="center">

### Let's build systems that scale — and understand why they work.

<a href="https://sanjay-kollimarla.vercel.app/">
<img src="https://img.shields.io/badge/Portfolio-Explore%20My%20Work-0F172A?style=for-the-badge&logo=vercel&logoColor=67E8F9" alt="Portfolio"/>
</a>
<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/LinkedIn-Let's%20Connect-0F172A?style=for-the-badge&logo=linkedin&logoColor=67E8F9" alt="LinkedIn"/>
</a>
<a href="https://github.com/sanjay-kollimarla">
<img src="https://img.shields.io/badge/GitHub-Follow%20My%20Work-0F172A?style=for-the-badge&logo=github&logoColor=67E8F9" alt="GitHub"/>
</a>

<img src="https://capsule-render.vercel.app/api?type=waving&height=100&section=footer&color=0:164E63,50:102A43,100:080D1A" width="100%" alt="Decorative footer"/>

<sub>Designed with an engineering mindset. Built to keep evolving.</sub>

</div>
