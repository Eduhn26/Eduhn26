<div align="center">

```
╔══════════════════════════════════════════════════════╗
║         EDUARDO HENRIQUE — BACKEND ENGINEER          ║
║    TypeScript · DDD · Clean Architecture · NestJS    ║
╚══════════════════════════════════════════════════════╝
```

<a href="https://www.linkedin.com/in/eduardohnascimento/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
<a href="mailto:duufhvo@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
<a href="https://github.com/Eduhn26">
  <img src="https://img.shields.io/badge/GitHub-161B22?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

---

## 👨‍💻 About Me

Backend developer focused on **architecture-oriented system design**, with solid foundations in **Domain-Driven Design (DDD)** and **Clean Architecture**.

My work isn't just about making things work — it's about making them **right**:

```
Domain integrity    →  Explicit invariants, no leaking state
Boundary discipline →  Layers that don't know each other's business
Error semantics     →  Meaningful failures, not silent bugs
Incremental design  →  Architecture that evolves without breaking
```

Started in the MERN ecosystem. Now building robust, typed, layered backend systems in TypeScript — with a strong preference for systems that are **readable in 6 months** and **testable without a running server**.

---

## 🧠 Engineering Principles

| Principle | What it means in practice |
|---|---|
| **Domain-first** | Business rules live in the domain — never in controllers or DB schemas |
| **Strict boundaries** | No leakage between layers. Infrastructure knows Application; Domain knows nothing |
| **Stateless auth** | JWT with role-based guards — no session state on the server |
| **Semantic errors** | `AppError` with status codes. No silent 500s with no context |
| **Phase-based evolution** | Architecture that grows by design, not by accident |

---

## 🛠️ Tech Stack

<div align="center">

| Backend & Core | Databases | Tooling |
| :---: | :---: | :---: |
| <img src="https://skillicons.dev/icons?i=ts,nodejs,nestjs,express" /> | <img src="https://skillicons.dev/icons?i=postgres,mongodb,prisma" /> | <img src="https://skillicons.dev/icons?i=git,github,docker,linux" /> |

</div>

---

## 🚀 Featured Projects

### 🃏 [Truco Paulista Backend](https://github.com/Eduhn26/truco-paulista-backend)

> Authoritative multiplayer backend for Truco Paulista — built phase by phase with architectural discipline.

```
Domain      →  Match, Hand, Round, Card, Score — pure TypeScript, zero framework deps
Application →  Use Cases (CreateMatch, PlayCard, JoinMatch, StartHand, GetRanking)
Infra       →  PrismaMatchRepository (PostgreSQL) + InMemoryMatchRepository (tests)
Transport   →  Socket.IO GameGateway — stateless, event-driven, real-time
```

**What makes it different:**
- Domain tested **without NestJS, without Prisma, without mocks** — just pure logic
- State persisted as **snapshot** in PostgreSQL — survives restarts
- Layered architecture enforced from **phase 0**, not retrofitted
- WebSocket gateway is **stateless** — domain lives in the DB, not in memory

**Stack:** `TypeScript` · `NestJS` · `Socket.IO` · `PostgreSQL` · `Prisma` · `Jest`  
**Pattern:** `Domain → Application → Infrastructure → Gateway`

---

### 🚚 [Fleet Scheduling System](https://github.com/Eduhn26/agendamento-frota)

> Corporate vehicle scheduling platform with real-world business rules and clean layered architecture.

```
Auth        →  JWT + role-based guards (admin / user)
Validation  →  Zod schemas at the boundary — invalid input never reaches the service
Errors      →  AppError with semantic status codes — no 500 catchalls
Business    →  Rental period limits, conflict detection, maintenance state machine
Separation  →  Routes → Middleware → Controllers → Services → Models
```

**What makes it different:**
- **Conflict detection** at service level — not just DB constraints
- **State machine** for vehicle status (available → rented → maintenance)
- **Refactored v2** with full Routes → Controllers → Services separation
- Global error handler — one place, consistent behavior

**Stack:** `Node.js` · `Express` · `MongoDB` · `Mongoose` · `Zod` · `JWT`  
**Pattern:** `Routes → Middleware → Controllers → Services → Models`

---

## 📊 GitHub Stats

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=Eduhn26&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Eduhn26&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF"/>
</div>

---

## 🎯 Current Focus

```typescript
const currentFocus = [
  'NestJS advanced patterns (Guards, Interceptors, Pipes)',
  'Hexagonal Architecture in production',
  'Automated testing strategies (unit → integration → e2e)',
  'Distributed systems fundamentals',
  'Observability: structured logging, health checks, metrics',
] as const;
```

---

<div align="center">

```
Engineering systems with intention, not just code.
```

</div>
