# Rudra Dave

Senior Android & Kotlin Multiplatform Engineer  
Building systems where AI intent meets deterministic mobile architecture.

---

## What I Build

I work at the intersection of **reliable mobile infrastructure** and **AI-powered decision logic**  systems that take unstructured user intent and turn it into consistent, real-world outcomes.

Core areas:
- Kotlin Multiplatform architecture (Android + iOS shared logic)
- Offline-first data systems with resilient sync
- LLM integration with deterministic ranking layers
- Full-stack Kotlin - Ktor backends, PostgreSQL, deployed and live
- Android build performance and developer tooling
- Fintech infrastructure: transactions, cards, exchange, sync

---

## Featured Work

### [SwiggyMind](https://github.com/rudradave1/SwiggyMind) - AI Food Ordering Copilot
Describe your craving in plain language. Get ranked, actionable recommendations.  
Built on Swiggy Builders Club using KMP + Compose + OpenRouter.

- Natural language → structured intent parsing via LLM
- Deterministic ranking layer for consistent, non-random outputs
- Mind Cache for stateful session memory across conversation turns
- Designed for decision-making, not browsing

→ Shows how LLMs can power real consumer workflows when paired with structured reasoning.

---

### [droidperf](https://github.com/rudradave1/droidperf) - Android Gradle Auditor
`npx droidperf audit` - detects and auto-fixes Android Gradle performance bottlenecks.

- Supports Android, KMP, and Flutter project shapes
- Writes only to `gradle.properties`; creates timestamped backups before any mutation
- CI-ready with `--json` output and `--dry-run` diff preview

→ 13 stars · 1 fork · ~15K views on r/androiddev within 24 hours of launch.

---

### [VellumLedger](https://github.com/rudradave1/VellumLedger) - Offline-First Finance + Live Backend
KMP expense tracker with a real deployed sync backend.

- Offline-first: every write lands in SQLDelight first, network is never a dependency
- SyncQueue pattern: `PENDING → SYNCING → SYNCED | FAILED` lifecycle per transaction
- Live Ktor + PostgreSQL backend on Railway with JWT auth and timestamp conflict resolution
- Biometric lock + SQLCipher database encryption

→ Complete end-to-end system in Kotlin. Backend: [vellum-ledger-api](https://github.com/rudradave1/vellum-ledger-api)

```bash
curl https://vellum-ledger-api-production.up.railway.app/health
```

---

### [KMP Fintech Starter](https://github.com/rudradave1/kmp-fintech-starter) - Production KMP Template
Offline-first fintech architecture for Android + iOS from a single shared codebase.

- Shared domain, repository, and presentation logic via KMP
- SQLDelight as local source of truth; Ktor for remote sync
- Koin DI, Clean Architecture, CI pipeline included

→ Production-grade starting point, not a demo - built to be forked and extended.

---

## Other Systems

| Project | What it is |
|---|---|
| [vellum-ledger-api](https://github.com/rudradave1/vellum-ledger-api) | Ktor sync backend for VellumLedger. PostgreSQL + Exposed ORM + JWT. Deployed on Railway. |
| [GeoRanker](https://github.com/rudradave1/GeoRanker) | KMP place ranking app. Custom scoring engine with explainable recommendations. SQLDelight + Google Maps. |
| [DefineEasy](https://github.com/rudradave1/DefineEasy) | Dictionary + spaced repetition. Live on Play Store. SM-2 scheduler, encrypted Room DB. |
| [QuikScore](https://github.com/rudradave1/QuikScore) | Floating live-score overlay. System overlay windows + background UI + real-time data. |
| [ParticleLab](https://github.com/rudradave1/ParticleLab) | Real-time physics simulation in Compose. Custom rendering, performance-focused architecture. |
| [smart-dnd-scheduler](https://github.com/rudradave1/smart-dnd-scheduler) | DND automation with AlarmManager, DataStore, and system-level permission handling. |
| [compose-production-template](https://github.com/rudradave1/compose-production-template) | Scalable Android template: Clean Architecture, Hilt, Room, Retrofit, WorkManager. |

---

## Engineering Approach

I design for **correctness first, then ergonomics**.

That means:
- Deterministic systems over probabilistic ones where predictability matters
- Local-first architecture so the app works regardless of network state
- Failure paths treated as first-class concerns, not edge cases
- Clear module boundaries so logic stays testable without platform dependencies

---

## Open to

**Remote Android / KMP engineering roles**  product teams building fintech, developer tools, or AI-integrated mobile experiences.  
Bhavnagar, India · Remote only.

---

## Stack

`Kotlin` · `Jetpack Compose` · `KMP` · `Ktor` · `SQLDelight` · `PostgreSQL` · `Room` · `WorkManager` · `Hilt` · `Koin` · `Coroutines/Flow` · `gRPC/Protobuf` · `Clean Architecture`

---

[GitHub](https://github.com/rudradave1) · [LinkedIn](https://www.linkedin.com/in/rudradave1) · [npm: droidperf](https://www.npmjs.com/package/droidperf)
