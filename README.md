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

### [Bomana](https://github.com/Thankyou-Cheems/Bomana) · War Thunder SB Timer

**战雷全真模式收益计时器**

War Thunder is a vehicle-combat video game; Bomana is a multifunction timer for simulator battles.<br>
Terms like “bomb / bombing / CCRP” here mean **in-game virtual concepts only**, not anything in the real world. Have fun!

War Thunder 是一款载具对战电子游戏；Bomana 是面向全真模式的多功能计时器。<br>
文中的「炸弹 / 投弹 / CCRP」等均指**游戏内虚拟概念**，与现实无关。祝你玩得开心！

<!-- Versions from EdgeOne CDN (what players actually get). GitHub "latest" is often a launcher-only tag. -->
[![App](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Fversion%3Fchannel%3DEnhanced&query=%24.app_version&label=app&prefix=v&color=0ea5e9)](https://ruikang.wang/bomana/)
[![Launcher](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Flauncher&query=%24.launcher_version&label=launcher&prefix=v&color=6366f1)](https://ruikang.wang/bomana/)
[![DAU](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Fstats%2Fdaily&query=%24.metrics.dau_unique_device&label=DAU&color=22c55e)](https://bomanaupdate.ruikang.wang/api/v1/stats/daily)
[![Launches](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fbomanaupdate.ruikang.wang%2Fapi%2Fv1%2Fstats%2Fdaily&query=%24.metrics.launcher_start_total&label=launches&color=3b82f6)](https://bomanaupdate.ruikang.wang/api/v1/stats/daily)
[![License](https://img.shields.io/badge/license-MIT-22c55e)](https://github.com/Thankyou-Cheems/Bomana/blob/main/LICENSE)

**[Site / CDN](https://ruikang.wang/bomana/)** ·
[GitHub Pages](https://thankyou-cheems.github.io/Bomana/) ·
[Repo](https://github.com/Thankyou-Cheems/Bomana) ·
[Releases](https://github.com/Thankyou-Cheems/Bomana/releases)

</div>

Open-source Windows companion for **War Thunder simulator battles**. It only reads the game’s official local `localhost:8111` HTTP data — no memory reads, injection, or game-file edits — and puts timer / navigation / fuel / overspeed cues in a lightweight always-on-top window (optional web cockpit on Enhanced).

- **15-minute reward cycle timer** with clear combat-state awareness  
- **Navigation & fuel cues** for zones / airfields and return-to-base planning  
- **Overspeed & weapon-range hints** (including CCRP-style engineering estimates where applicable)  
- **Signed portable launcher** with channel selection (Enhanced / Standard / Lite), auto-update, and rollback  
- **China-friendly distribution** via Tencent EdgeOne CDN (`bomanaupdate.ruikang.wang`) with GitHub as backup  

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
