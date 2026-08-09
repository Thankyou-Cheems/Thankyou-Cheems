<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=2800&pause=1200&color=58A6FF&center=true&vCenter=true&repeat=true&width=640&height=52&lines=Hi%2C+I%27m+Ruikang+%28Karl%29+Wang" alt="Typing SVG" />
</a>

**M.S. in Artificial Intelligence @ Columbia University**  
**Inaugural Cohort · Fall 2026**

**AI doesn’t replace thinking, it Amplifies.**

[![Email](https://img.shields.io/badge/me@ruikang.wang-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:me@ruikang.wang)
[![LinkedIn](https://img.shields.io/badge/ruikangwang-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ruikangwang/)
[![X](https://img.shields.io/badge/@thankyucheems-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/thankyucheems)
[![Portfolio](https://img.shields.io/badge/ruikang.wang-4285F4?style=flat-square&logo=googlechrome&logoColor=white)](https://ruikang.wang)

</div>

---

## Current interests

- **Agentic Coding Infrastructure** — task graphs, structured memory, multi-step coding workflows, and repo-aware agent tooling
- **Context Engineering** — selecting, compressing, and routing project context under token, latency, and reliability constraints
- **LLM Reliability & Evaluation** — traces, replayable workflows, failure analysis, regression tests, and agent observability
- **Inference & Cost Engineering** — model routing, caching, latency/cost tradeoffs, and production-oriented LLM serving fundamentals

---

## Open Source

### [beads](https://github.com/steveyegge/beads) — Structured task memory for coding agents

Contributed reliability and developer-experience improvements to a Go-based structured task-memory system for AI coding agents.

- **Storage reliability** — migrated doctor maintenance checks from JSONL to Dolt-native storage with fallback ([#2146](https://github.com/steveyegge/beads/pull/2146))
- **CLI safety** — fixed `--yes` being ignored during non-interactive repo fingerprint repair ([#1782](https://github.com/steveyegge/beads/pull/1782))
- **Sync consistency** — fixed DB/mtime checks under sync-branch mode ([#1695](https://github.com/steveyegge/beads/pull/1695), closes [#1667](https://github.com/steveyegge/beads/issues/1667))

### Other OSS

- [EasyTier](https://github.com/EasyTier/EasyTier) `Rust` — improved Magisk route-rule idempotency and fixed module status behavior ([#1927](https://github.com/EasyTier/EasyTier/pull/1927))

---

## Featured Project

<div align="center">

<img src="https://raw.githubusercontent.com/Thankyou-Cheems/Bomana/main/bomana/assets/branding/app.png" width="96" alt="Bomana app icon">

### [Bomana](https://github.com/Thankyou-Cheems/Bomana) · War Thunder Simulator Companion

**战雷全真模式计时、导航与飞行辅助**

Windows companion for War Thunder simulator battles, built around the game's official local
`localhost:8111` HTTP interface — no memory reads, injection, game-file edits, or game-input automation.

<!-- Public versions come from the live EdgeOne endpoints. Enhanced is intentionally not exposed there. -->
[![Public App](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Fversion%3Fchannel%3DStandard&query=%24.app_version&label=public%20app&prefix=v&color=0ea5e9&style=flat-square&cacheSeconds=300)](https://bomana.ruikang.wang/)
[![Public Launcher](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Flauncher&query=%24.launcher_version&label=public%20launcher&prefix=v&color=6366f1&style=flat-square&cacheSeconds=300)](https://bomana.ruikang.wang/)
[![Enhanced](https://img.shields.io/badge/Enhanced-subscriber%20delivery-f59e0b?style=flat-square)](https://bomana.ruikang.wang/#channels)
[![Product DAU](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Fstats%2Fdaily&query=%24.metrics.dau_unique_device&label=product%20DAU&color=22c55e&style=flat-square&cacheSeconds=300)](https://bomanaupdate.ruikang.wang/api/v1/stats/daily)

**[Website & Download](https://bomana.ruikang.wang/)** ·
[Public Source](https://github.com/Thankyou-Cheems/Bomana) ·
[Releases](https://github.com/Thankyou-Cheems/Bomana/releases) ·
[Privacy](https://github.com/Thankyou-Cheems/Bomana/blob/main/docs/PRIVACY.md)

<sub>“Bomb / bombing / CCRP” refers only to in-game virtual mechanics.</sub>

</div>

### One product, two delivery boundaries

| Open-source editions | Enhanced subscriber edition |
| :--- | :--- |
| **Lite / Standard** | **Super Bomb / Enhanced** |
| Public source and release artifacts under the MIT License. | Maintained in a separate private repository with controlled subscriber delivery. |
| Reward-cycle timer, navigation, fuel, and overspeed cues. | Adds offline terrain, weapon-reference estimates, and Web Cockpit. |
| [Source](https://github.com/Thankyou-Cheems/Bomana) · [Public releases](https://github.com/Thankyou-Cheems/Bomana/releases) · [Docs](https://github.com/Thankyou-Cheems/Bomana#readme) | [Product details](https://bomana.ruikang.wang/#channels) · [Purchase / trial](https://pay.ruikang.wang/) |

> **Unified product metric, separate delivery:** DAU intentionally aggregates public and Enhanced
> editions. Source access, repositories, licensing, and release artifacts remain separate.

Public Lite / Standard releases use Tencent EdgeOne for China-friendly delivery with GitHub fallback;
Enhanced artifacts remain on subscriber-only infrastructure.

---

## Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Cloudflare](https://img.shields.io/badge/CF_Workers-F38020?style=flat&logo=cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

![LLM Evals](https://img.shields.io/badge/LLM_Evals-6E40C9?style=flat)
![Agentic Coding](https://img.shields.io/badge/Agentic_Coding-58A6FF?style=flat)
![Context Engineering](https://img.shields.io/badge/Context_Engineering-2EA043?style=flat)
![Developer Tools](https://img.shields.io/badge/Developer_Tools-F78166?style=flat)
![Observability](https://img.shields.io/badge/Observability-8B949E?style=flat)

---

<div align="center">

![Profile Views](https://komarev.com/ghpvc/?username=Thankyou-Cheems&style=flat-square&color=58A6FF)

</div>
