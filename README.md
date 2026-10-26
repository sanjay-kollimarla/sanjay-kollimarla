
<!--
  SANJAY KOLLIMARLA | FUTURISTIC ENGINEERING PROFILE
  Theme: Midnight glass / Electric cyan / Neon violet / Magenta
-->

<div align="center">

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=wave&height=240&color=0:070B17,30:10243E,65:312E81,100:701A75&text=SANJAY%20KOLLIMARLA&fontSize=40&fontColor=67E8F9&fontAlignY=38&desc=BACKEND%20ENGINEERING%20%2F%2F%20DISTRIBUTED%20SYSTEMS&descSize=14&descColor=E9D5FF&descAlignY=58&animation=fadeIn" width="100%" alt="Sanjay Kollimarla — Backend Software Engineer"/>

<!-- <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=2600&pause=700&color=67E8F9&center=true&vCenter=true&width=850&lines=Building+Reliable+Backend+Systems;Engineering+Distributed+Processing+Pipelines;Designing+for+Scale%2C+Failure+%26+Performance" alt="Animated engineering tagline"/> -->

</div>
<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=17&duration=2600&pause=700&color=67E8F9&center=true&vCenter=true&width=850&lines=Building+Reliable+Backend+Systems;Engineering+Distributed+Processing+Pipelines;Node.js+%7C+TypeScript+%7C+Redis+%7C+MongoDB;Designing+for+Scale%2C+Failure+%26+Performance;Turning+Complexity+Into+Maintainable+Systems" alt="Animated engineering tagline"/>

<br/><br/>

<a href="https://sanjay-kollimarla.vercel.app/">
<img src="https://img.shields.io/badge/PORTFOLIO-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
</a>
<a href="https://linkedin.com/in/kollimarla-sai-sanjay">
<img src="https://img.shields.io/badge/LINKEDIN-0891B2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/sanjay-kollimarla?tab=repositories">
<img src="https://img.shields.io/badge/EXPLORE_PROJECTS-DB2777?style=for-the-badge&logo=github&logoColor=white" alt="Projects"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/FOCUS-DISTRIBUTED%20SYSTEMS-10243E?style=flat-square&labelColor=070B17" alt="Distributed systems"/>
<img src="https://img.shields.io/badge/CRAFT-BACKEND%20ENGINEERING-312E81?style=flat-square&labelColor=070B17" alt="Backend engineering"/>
<img src="https://img.shields.io/badge/MINDSET-RELIABILITY%20%26%20SCALE-701A75?style=flat-square&labelColor=070B17" alt="Reliability and scale"/>

</div>

---

<div align="center">

## `01` — ENGINEERING IDENTITY

### Engineering beyond the happy path.

*Scalable architecture. Predictable failure recovery. Measurable performance.*

</div>

I'm **Sanjay Kollimarla**, a software engineer with 3+ years of experience building web applications and backend services.

My engineering focus is on designing maintainable backend systems, asynchronous processing pipelines, and distributed services. I enjoy investigating what happens beyond a successful API response: how concurrent operations remain correct, how queues recover from failure, how caching affects consistency, and how systems behave under load.

I believe strong engineering is about more than making software work. It's about understanding **why it works, when it fails, and how it recovers**.

<table>
<tr>
<td width="50%" valign="top">

### ◈ SYSTEMS THINKING

- Distributed service architecture
- Asynchronous processing
- Concurrency and consistency
- Fault isolation and recovery
- API contracts and authorization

</td>
<td width="50%" valign="top">

### ◈ PERFORMANCE THINKING

- Database indexing and query tuning
- Caching strategies
- Throughput and latency analysis
- Resource-efficient processing
- Reproducible benchmarking

</td>
</tr>
</table>

---

<div align="center">

## `02` — THE TECHNOLOGY MATRIX

*Tools are implementation details. Engineering fundamentals are the foundation.*

</div>

<div align="center">

### LANGUAGES

<img src="https://skillicons.dev/icons?i=ts,js,java,python&theme=dark" alt="TypeScript JavaScript Java Python"/>

### BACKEND ENGINEERING

<img src="https://skillicons.dev/icons?i=nodejs,express,bun&theme=dark" alt="Node.js Express Bun"/>

### DATA & CACHING

<img src="https://skillicons.dev/icons?i=mongodb,mysql,redis&theme=dark" alt="MongoDB MySQL Redis"/>

### CLOUD & INFRASTRUCTURE

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,git,github,linux&theme=dark" alt="AWS Docker Kubernetes Git GitHub Linux"/>

</div>

<table>
<tr>
<td width="33%" valign="top">

**BACKEND**

Node.js · Express.js · Hono · Bun · REST APIs · WebSockets · SSE · Webhooks

</td>
<td width="33%" valign="top">

**DATA SYSTEMS**

MongoDB · MySQL · Redis · Indexing · Aggregation · Caching · Data Modeling

</td>
<td width="33%" valign="top">

**ENGINEERING**

BullMQ · Lua · Docker · AWS · Kubernetes · CI/CD · System Design · DSA

</td>
</tr>
</table>

---

<div align="center">

## `03` — FEATURED ENGINEERING PROJECTS

*Three systems. Three different engineering challenges.*

</div>

<table>
<tr>
<td colspan="2" valign="top">

<h3>01 / DISTRIBUTED EMAIL QUEUE PLATFORM</h3>

<img src="https://img.shields.io/badge/BULLMQ-7C3AED?style=flat-square" alt="BullMQ"/>
<img src="https://img.shields.io/badge/REDIS-DC2626?style=flat-square" alt="Redis"/>
<img src="https://img.shields.io/badge/TYPESCRIPT-2563EB?style=flat-square" alt="TypeScript"/>
<img src="https://img.shields.io/badge/DOCKER-0891B2?style=flat-square" alt="Docker"/>

A distributed job-processing platform focused on reliable asynchronous execution, controlled concurrency, and failure recovery.

**ENGINEERING CHALLENGES**

- Retry policies with exponential backoff
- Dead-letter handling and failed-job inspection
- Idempotency and duplicate-execution protection
- Worker concurrency and priority queues
- Rate limiting and controlled throughput
- Real-time job status via SSE and webhooks

**SYSTEM FLOW**

`API → Queue → Redis → Workers → Processing → Status Events`

The central design challenge is ensuring that transient failures, worker restarts, duplicate requests, and downstream service errors are handled deliberately rather than left to chance.

<div align="center">

<a href="YOUR_EMAIL_QUEUE_REPO_URL">
<img src="https://img.shields.io/badge/INSPECT_SOURCE-67E8F9?style=for-the-badge&logo=github&logoColor=070B17" alt="Inspect email queue source"/>
</a>

</div>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<h3>02 / DISTRIBUTED RATE LIMITING SERVICE</h3>

<img src="https://img.shields.io/badge/REDIS-DC2626?style=flat-square" alt="Redis"/>
<img src="https://img.shields.io/badge/LUA-0891B2?style=flat-square" alt="Lua"/>
<img src="https://img.shields.io/badge/NODE.JS-15803D?style=flat-square" alt="Node.js"/>
<img src="https://img.shields.io/badge/EXPRESS-64748B?style=flat-square" alt="Express"/>

A centralized rate-limiting service designed to enforce request policies consistently across multiple application instances.

**ENGINEERING CHALLENGES**

- Token Bucket and Sliding Window algorithms
- Atomic Redis operations using Lua scripts
- Per-client limits and configurable policies
- Concurrent request handling
- Expiration and state cleanup
- Performance testing and boundary-condition validation

**SYSTEM FLOW**

`Client → Middleware → Policy Evaluation → Atomic Redis Operation → Allow / Reject`

The key design problem is preventing concurrent requests from bypassing limits while keeping request processing efficient.

<div align="center">

<a href="YOUR_RATE_LIMITER_REPO_URL">
<img src="https://img.shields.io/badge/INSPECT_SOURCE-A78BFA?style=for-the-badge&logo=github&logoColor=070B17" alt="Inspect rate limiter source"/>
</a>

</div>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<h3>03 / DISTRIBUTED URL SHORTENING SERVICE</h3>

<img src="https://img.shields.io/badge/MONGODB-15803D?style=flat-square" alt="MongoDB"/>
<img src="https://img.shields.io/badge/REDIS-DC2626?style=flat-square" alt="Redis"/>
<img src="https://img.shields.io/badge/AWS-CA8A04?style=flat-square" alt="AWS"/>
<img src="https://img.shields.io/badge/DOCKER-0891B2?style=flat-square" alt="Docker"/>

A URL-shortening backend focused on efficient redirects, cache behavior, identifier generation, and asynchronous analytics.

**ENGINEERING CHALLENGES**

- Short-code generation and collision handling
- Persistent storage and expiration policies
- Redis caching for redirect lookups
- Cache invalidation and cache-miss behavior
- Asynchronous click analytics
- Duplicate detection and link lifecycle management

**SYSTEM FLOW**

`Create Link → Generate Code → Persist → Cache → Redirect → Analytics`

The design separates the latency-sensitive redirect path from secondary analytics work while considering expired links, cache misses, and storage failures.

<div align="center">

<a href="YOUR_URL_SHORTENER_REPO_URL">
<img src="https://img.shields.io/badge/INSPECT_SOURCE-F0ABFC?style=for-the-badge&logo=github&logoColor=070B17" alt="Inspect URL shortener source"/>
</a>

</div>

</td>
</tr>
</table>

---

<div align="center">

## `04` — ENGINEERING PRINCIPLES

</div>

<table>
<tr>
<td width="50%" valign="top">

### 01 / CORRECTNESS

Establish invariants, define contracts, and understand edge cases before optimizing.

### 02 / RESILIENCE

Treat retries, timeouts, partial failures, and recovery as explicit design concerns.

### 03 / CONCURRENCY

Reason about shared state, atomic operations, race conditions, and duplicate execution.

</td>
<td width="50%" valign="top">

### 04 / PERFORMANCE

Measure representative workloads and use evidence to guide optimization.

### 05 / MAINTAINABILITY

Prefer clear abstractions, explicit dependencies, and separation of responsibilities.

### 06 / OBSERVABILITY

Use structured logging, useful error context, and metrics to make failures diagnosable.

</td>
</tr>
</table>

---

<div align="center">

## `05` — GITHUB TELEMETRY

*Live profile statistics, subject to third-party service availability.*

<img src="https://github-readme-stats.vercel.app/api?username=sanjay-kollimarla&show_icons=true&hide_border=true&bg_color=070B17&title_color=67E8F9&text_color=C9D1D9&icon_color=A78BFA&rank_icon=github&include_all_commits=true" height="170" alt="GitHub statistics"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sanjay-kollimarla&layout=compact&hide_border=true&bg_color=070B17&title_color=F0ABFC&text_color=C9D1D9" height="170" alt="GitHub language statistics"/>

<img src="https://streak-stats.demolab.com?user=sanjay-kollimarla&hide_border=true&background=070B17&ring=67E8F9&fire=F0ABFC&currStreakLabel=67E8F9&sideLabels=C9D1D9&dates=94A3B8&currStreakNum=FFFFFF&sideNums=A78BFA" width="85%" alt="GitHub contribution streak"/>

</div>

---

<div align="center">

## `06` — CONTRIBUTION ACTIVITY

<img src="https://raw.githubusercontent.com/sanjay-kollimarla/sanjay-kollimarla/output/github-snake-dark.svg" width="100%" alt="Animated GitHub contribution snake"/>

<sub>The contribution animation appears after the GitHub Actions workflow generates and publishes the SVG.</sub>

</div>

---

<div align="center">

## `07` — ENGINEERING MINDSET

</div>

```text
Readable code        > Unnecessary cleverness
Measured performance > Assumptions about speed
Explicit contracts   > Hidden dependencies
Reliable recovery    > Happy-path-only design
Useful abstractions  > Accidental complexity
```

I'm interested in backend engineering, distributed systems, system design, and collaborating with engineers who value technical depth, ownership, and continuous improvement.

---

<div align="center">

## LET'S CONNECT

### Building reliable systems starts with understanding the hard problems.

<a href="https://sanjay-kollimarla.vercel.app/">
<img src="https://img.shields.io/badge/EXPLORE_PORTFOLIO-7C3AED?style=for-the-badge&logo=vercel&logoColor=white" alt="Explore portfolio"/>
</a>
<a href="YOUR_LINKEDIN_URL">
<img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-0891B2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn"/>
</a>
<a href="https://github.com/sanjay-kollimarla?tab=repositories">
<img src="https://img.shields.io/badge/EXPLORE_GITHUB-DB2777?style=for-the-badge&logo=github&logoColor=white" alt="Explore GitHub repositories"/>
</a>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:701A75,50:312E81,100:070B17" width="100%" alt="Futuristic gradient footer"/>

<sub>Designed around engineering. Built to evolve.</sub>

</div>
