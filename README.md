<a id="readme-top"></a>

<div align="center">

# Rudra Dave

### Senior Android & Kotlin Multiplatform Engineer

**I build, ship, and maintain mobile products.**

Android · Kotlin · Jetpack Compose · Kotlin Multiplatform · AI

<br />

[![GitHub Followers](https://img.shields.io/github/followers/rudradave1?style=for-the-badge&logo=github&label=FOLLOWERS)](https://github.com/rudradave1?tab=followers)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rudradave/)
[![Play Store](https://img.shields.io/badge/PLAY%20STORE-414141?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/dev?id=5957333055367817229)

</div>

<br />

---

## Table of Contents

* [About Me](#about-me)
* [Products I've Shipped](#products-ive-shipped)
* [Selected Work & Tooling](#selected-work--tooling)
* [What I Work With](#what-i-work-with)
* [How I Build](#how-i-build)
* [Contact](#contact)

---

## About Me

I'm a **Senior Android & Kotlin Multiplatform Engineer** with 6+ years of software engineering experience.

For four years, I worked as the primary Android engineer at a fintech startup, taking mobile products from architecture and implementation through releases and production.

I focus on the entire product lifecycle:

**Idea → Architecture → Implementation → Polish → Release → Production**

My work spans native Android, Kotlin Multiplatform, Jetpack Compose, local-first data architecture, background processing, developer tooling, and production apps on Google Play.

---

## Products I've Shipped

Three independent products currently live on Google Play, each built to solve a distinct product and technical challenge.

<table>
<tr>

<td width="33%" align="center" valign="top">

### Sotto

**Private Voice Journal**

Capture thoughts by simply speaking.

KMP · Compose · AI · Privacy

<br />

<a href="https://play.google.com/store/apps/details?id=com.sotto.memories">
<img src="https://img.shields.io/badge/GOOGLE%20PLAY-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Sotto on Google Play">
</a>

</td>

<td width="33%" align="center" valign="top">

### Aura RNG

**RNG Game**

A native Android game built around rolling, collecting, crafting, and progression. Zero production crashes.

Kotlin · Compose · DataStore

<br />

<a href="https://play.google.com/store/apps/details?id=com.rudra.aurarng">
<img src="https://img.shields.io/badge/GOOGLE%20PLAY-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Aura RNG on Google Play">
</a>

</td>

<td width="33%" align="center" valign="top">

### Vellum Ledger

**Personal Finance**

A Kotlin Multiplatform finance application focused on structured personal money management and queued sync.

KMP · Compose · SQLDelight

<br />

<a href="https://play.google.com/store/apps/details?id=com.vellum.ledger">
<img src="https://img.shields.io/badge/GOOGLE%20PLAY-414141?style=for-the-badge&logo=google-play&logoColor=white" alt="Vellum Ledger on Google Play">
</a>

</td>

</tr>
</table>

<p align="center">
  <sub>Built independently to explore different product, engineering, and architecture problems.</sub>
</p>

---

## Selected Work & Tooling

### [proguard-lint](https://github.com/rudradave1/proguard-lint)

**High-performance R8 / ProGuard verification plugin**

An open-source Gradle plugin (AGP 8.0+) that audits ProGuard/R8 obfuscation and shrinking quality directly from `mapping.txt` and `seeds.txt` artifacts.

* Built with 27 automated integration tests.
* Runs deterministically in under 250ms during release build checks.

**Kotlin · Gradle Plugin API · AGP 8.0+ · Bytecode & R8 Analysis**

---

### [droidperf](https://github.com/rudradave1/droidperf)

**Android build performance CLI**

[npm package](https://www.npmjs.com/package/droidperf)

A developer tool that audits Android projects for Gradle performance bottlenecks and automatically applies safe configuration fixes.

```bash
npx droidperf audit
```

```text
Scanning your Android project...

Found 7 issues costing you ~3.0 minutes per build:

[CRITICAL] Configuration cache disabled
[CRITICAL] Build cache disabled
[HIGH]     Parallel execution disabled
[HIGH]     Kotlin incremental disabled
[MEDIUM]   JVM heap too low

Estimated waste: 3.0 min/build
```

**Kotlin · Gradle · Node.js · CLI**

---

### [kmp-fintech-starter](https://github.com/rudradave1/kmp-fintech-starter)

**Kotlin Multiplatform fintech foundation**

A production-oriented KMP starter covering the architectural foundations needed for complex mobile systems: offline-first synchronization, secure data storage, and strict layer decoupling.

`SQLDelight` · `Ktor` · `Koin` · `Clean Architecture` · `CI`

---

### [compose-production-template](https://github.com/rudradave1/compose-production-template)

**Production Android foundation**

A modular Android template built around production best practices:

`Jetpack Compose` · `Clean Architecture` · `Hilt` · `Room` · `Retrofit` · `WorkManager` · `CI`

---

### [SwiggyMind](https://github.com/rudradave1/SwiggyMind)

**AI food discovery copilot**

An AI-powered food recommendation experiment built for Swiggy Builders Club. Interprets natural language constraints, ranks options, and returns explainable recommendations.

**Kotlin Multiplatform · Compose · OpenRouter**

---

### [GeoRanker](https://github.com/rudradave1/GeoRanker)

**Explainable recommendation engine**

A KMP place discovery application focused on transparent ranking algorithms and explainable recommendation mechanics.

**Kotlin Multiplatform · Compose Multiplatform · Ranking Systems**

---

## What I Work With

<div align="center">

### Android & Multiplatform

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com/)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/develop/ui/compose)
[![Kotlin Multiplatform](https://img.shields.io/badge/Kotlin%20Multiplatform-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org/docs/multiplatform.html)

### Architecture & Infrastructure

[![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=for-the-badge&logo=ktor&logoColor=white)](https://ktor.io/)
[![SQLDelight](https://img.shields.io/badge/SQLDelight-4EAA25?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqldelight.github.io/sqldelight/)
[![Hilt](https://img.shields.io/badge/Hilt-009639?style=for-the-badge&logo=dagger&logoColor=white)](https://dagger.dev/hilt/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)](https://gradle.org/)

### Product & Tooling

[![OpenRouter](https://img.shields.io/badge/OpenRouter-111111?style=for-the-badge)](https://openrouter.ai/)
[![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)

</div>

---

## How I Build

<table>
<tr>

<td width="50%" valign="top">

### Product First

I build applications people can actually use, not just architecture demos.

That means thinking through the user experience, offline resilience, edge cases, distribution, analytics, and what happens post-release.

</td>

<td width="50%" valign="top">

### Engineering Depth

Architecture should make a codebase easier to evolve and scale.

I care about decoupled boundaries, maintainable multi-module setups, predictable state flow, and systems that behave correctly when the network fails.

</td>

</tr>

<tr>

<td width="50%" valign="top">

### Ship It

An idea on a local machine remains an experiment.

A product live on Google Play is real.

I take ownership of projects all the way to release builds and live distribution.

</td>

<td width="50%" valign="top">

### Continuous Exploration

My independent projects explore different problem spaces.

Games, finance, voice, AI, developer tooling, and KMP each provide distinct architectural challenges that sharpen my day-to-day engineering.

</td>

</tr>
</table>

---

## Currently

<div align="center">

### Building at the intersection of

**Android · Kotlin · KMP · AI · Product Engineering**

I'm interested in building products where strong software engineering and modern technology create something genuinely useful.

</div>

---

## Contact

<div align="center">

### Rudra Dave

<a href="https://www.linkedin.com/in/rudradave/">
<img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>

<a href="https://github.com/rudradave1">
<img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

<a href="mailto:rudramordan@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br />
<br />

**Open to remote Android, Kotlin, and KMP engineering opportunities.**

</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
