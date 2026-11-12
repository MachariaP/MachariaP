# Phinehas Macharia

**Backend developer building payments-integrated, multi-tenant systems for Kenyan and African businesses: M-Pesa, POS and real-time services in Python.**

Backend Developer at PeerNest · ALX Africa Software Engineering graduate · Nairobi, Kenya 🇰🇪

---

## What I do

- Build money-handling backends in **FastAPI** and **Django/DRF**: idempotent checkout, shifts, inventory ledgers, loans and contributions, audit trails.
- Integrate **M-Pesa (Daraja)**: STK Push, status queries, callback handling, bulk payments and reconciliation.
- Isolate each business's data in **multi-tenant** systems, and prove it with tenant-isolation tests.
- Ship real-time and event-driven services with **WebSockets and Apache Kafka**, containerised with Docker and gated by CI.

## Selected work

| Project | What it shows | Stack |
| --- | --- | --- |
| **BizPo** *(private)* | Point-of-sale backend for small retail: organisation-scoped data, atomic idempotent checkout, shifts, stock movements, purchase orders, a Daraja STK adapter with per-organisation encrypted credentials. CI runs Ruff, mypy, a secret scan and a 90% coverage gate. M-Pesa is at sandbox stage. | FastAPI, PostgreSQL, Alembic, React |
| **[ChamaHub](https://github.com/MachariaP/ProDev-Backend)** | Backend for Kenyan savings groups: contributions, loans, fines, voting, multi-signature disbursement approvals, and an M-Pesa app covering STK Push, C2B callbacks, bulk payments and reconciliation. | Django 5, DRF, Celery, Redis, Channels |
| **PeerNest Chat Service** *(private)* | Real-time chat microservice: WebSocket gateway plus five Kafka consumer services (persistence, moderation, rooms, counters, gateway), Alembic migrations, Docker Compose. | FastAPI, aiokafka, PostgreSQL |
| **Rasova Restaurant POS** *(private)* | Multi-tenant restaurant SaaS: tenant-scoped middleware, one tax engine, thermal printing, Celery jobs, over 2,000 tests and CI. | Django 6, PostgreSQL, Celery, Redis |
| **[WeatherAI](https://github.com/MachariaP/weatherai-platform)** ([live](https://weatherai-platform.vercel.app)) | A FastAPI gateway with timeouts, retries, caching, rate limiting and a circuit breaker in front of third-party APIs. Ruff, pytest, Vitest and Playwright in CI. | FastAPI, Next.js, TypeScript |
| **[LinkedIntel API](https://github.com/MachariaP/linked-intel-api)** | Job-application tracking API: idempotent upserts, API-key auth, throttling, audit log, OpenAPI docs, 102 tests on every push. | Django, DRF, GitHub Actions |

Also built: **Mauzo**, a multi-branch retail ERP with M-Pesa STK Push (private, TypeScript, Fastify, Prisma), and **[System Design Academy](https://github.com/MachariaP/system-design-academy)**, a distributed-systems curriculum with tested Python implementations.

*Private projects are available for a walkthrough on request.*

## Tech stack

| | |
| --- | --- |
| **Backend** | Python, FastAPI, Django, Django REST Framework, Flask, Node.js (Express, Fastify), JWT auth |
| **Payments** | M-Pesa Daraja (STK Push, C2B, bulk payments) |
| **Data and messaging** | PostgreSQL, Prisma, Alembic, MongoDB, Redis, Apache Kafka, RabbitMQ, Celery, WebSockets |
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS |
| **DevOps** | Docker, Docker Compose, GitHub Actions, Render, Vercel |
| **Testing** | pytest, Vitest, Playwright, Ruff, mypy |

## Let's work together

I'm open to backend roles and freelance work: API builds, M-Pesa and payment integrations, multi-tenant systems.

- Portfolio: [sites-r7xt.onrender.com](https://sites-r7xt.onrender.com)
- GitHub: [@MachariaP](https://github.com/MachariaP)
- Email: [walburphinehas78@gmail.com](mailto:walburphinehas78@gmail.com)
- LinkedIn: [phinehas-macharia](https://linkedin.com/in/phinehas-macharia)
- X: [@_M_Phinehas](https://x.com/_M_Phinehas)
