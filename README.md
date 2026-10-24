<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/hero-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/hero-light.svg" alt="Star — small, inspectable tools, AI companions and reproducible experiments" width="100%">
  </picture>
</p>

<p align="center">
  <a href="#-off-the-keyboard"><img alt="local-first by default" src="https://img.shields.io/badge/local--first-by%20default-6D28D9?style=flat-square"></a>
  <a href="#-how-i-build"><img alt="evidence-led, no faked dones" src="https://img.shields.io/badge/evidence--led-no%20faked%20dones-0E7490?style=flat-square"></a>
  <a href="#-how-i-build"><img alt="checkpoint then change then rollback" src="https://img.shields.io/badge/checkpoint%20%E2%86%92%20change%20%E2%86%92%20rollback-B45309?style=flat-square"></a>
  <img alt="Cantonese, Japanese, English" src="https://img.shields.io/badge/%E5%BB%A3%E6%9D%B1%E8%A9%B1%20%C2%B7%20%E6%97%A5%E6%9C%AC%E8%AA%9E%20%C2%B7%20English-4B5563?style=flat-square">
</p>

## Sup , Star957 here 👋

I build small, inspectable tools — and then write down exactly where they stop working.
Windows automation, local-first AI companions, 3D/2D avatar pipelines, offline learning, and
reproducible Python experiments. Everything here ships with its tests, its assumptions, and its limits.

繁體中文／廣東話：呢度集中放技術報告同可檢查嘅工具。每份報告分清楚實測、作者聲稱、推論同未驗證部分 —— 唔會用「好似行得通」當證據。

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg" alt="" width="100%">
  </picture>
</p>

## ⚡ Off the keyboard

The code above doesn't come from nowhere. It comes from curiosity that mostly shows up after midnight.

| | |
| --- | --- |
| 🎮 **Gacha & open worlds** | Arknights · Arknights: Endfield · Wuthering Waves · Zenless Zone Zero · Skyrim (heavily modded, three installs deep) |
| 🧱 **Minecraft megabuilds** | An orbital-city / space-elevator build driven by generated datapacks — ~200,000 block fills, plus my own palette and blockstate validation tooling |
| 🧍 **3D & 2D avatar craft** | Blender · VRM · MMD · Live2D — PMX→VRM conversion, MToon shading, springbone hair, expression morphs |
| 🤖 **AI companions & VTubers** | Local-first companion systems; and a video-audit method built on an auditable denominator and pixel-grounded coverage, instead of sampling a few clips |
| 🖥️ **Desktop pets & window craft** | Companions that surface live agent/terminal activity on screen; a taskbar tuned until it politely disappears |
| 🚗 **JDM & 改裝 culture** | Modification over stock, pop-up headlights, white leather with Tiffany-blue stitching. Dream garages only — I've never driven one |
| 🎬 **Making things for people** | Short-form humour writing and editing — an interest, not yet a track record. Much happier *behind* the camera than in front of it |
| 🌙 **Night owl** | The quiet hours are when the real work actually happens |

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg" alt="" width="100%">
  </picture>
</p>

## 🧪 How I build

**Evidence has layers.** An offline check, a simulated run, a live run and a human acceptance are four
different claims. A green test suite proves its stated case — never universal safety, visual acceptance
or production readiness. I keep those layers apart on purpose.

**Never fake a "done".** If it isn't verified, it's labelled unverified. Static proof is not acceptance.

**Checkpoint → change → rollback.** A backup, a hash and a way back exist *before* anything is overwritten.

**Maker ≠ checker.** Whoever wrote it doesn't get to be the only one who approves it.

**Genuine RED → GREEN.** A test that never failed first isn't a test.

**Local-first, fail-closed.** Private material stays private. Publishing is a deliberate act, not a default.

**Show the work.** No confetti and no decoration standing in for evidence — just what ran, what it proved, and what it didn't.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg" alt="" width="100%">
  </picture>
</p>

## 📌 Start with the reports

| Topic | Read | What to expect |
| --- | --- | --- |
| **Lian Li LED & LCD control** | [Windows lighting report](https://github.com/Star-957/led-control/blob/main/docs/lian-li-tl-wireless-lcd-lighting.md) | How TL Wireless LCD lighting, fan rings and screen backlights differ; preserve images while switching illumination |
| **AI companion memory & learning** | [小凌：記憶更正、有限心流與技能學習](https://github.com/Star-957/ai-companion-research/blob/main/reports/2026-10-22-xiaoling-ai-companion.zh-HK.md) | Dated public-source research; distinguishes demonstrations, creator claims and proposed experiments |
| **Retirement Monte Carlo experiments** | [Model and limitations](https://github.com/Star-957/retirement-monte-carlo-lab) · [10,000-path example](https://github.com/Star-957/retirement-monte-carlo-lab/blob/main/examples/demo__e6082db952396669/report.md) | Normalized balances, disclosed assumptions and hash-verified outputs; not personal financial advice or a guarantee |
| **Orthogonal geometry validation** | [Box-union checks and synthetic tests](https://github.com/Star-957/orthogonal-geometry-checks) | Directed boundaries, winding and explicit representation rules; floating-point checks, not general mesh or game-runtime certification |

## 🧰 More code to explore

| Project | Scope |
| --- | --- |
| [Video Evidence Toolkit](https://github.com/Star-957/video-evidence-toolkit) | Long-form video acquisition and visual-coverage validation, with 144 offline regression checks. No media or research records included |
| [Multi-AI Hub](https://github.com/Star-957/multi-ai-hub) | Local-first MCP coordination and bounded review workflows |
| [Companion Task Console](https://github.com/Star-957/companion-task-console) | Synthetic task replay and an original geometric desktop-companion UI |
| [Synthetic Withdrawal Simulations](https://github.com/Star-957/synthetic-withdrawal-simulations) | Monte Carlo withdrawal experiments with deterministic terminal-loss regression tests |
| [Trading Sim Companion](https://github.com/Star-957/trading-sim-companion) | Offline synthetic event replay; no real accounts, orders or market feed |
| [NihongoQuest Offline](https://github.com/Star-957/nihongoquest-offline) | Japanese-practice core with synthetic lessons and local progress |
| [Dual-Lane Captions](https://github.com/Star-957/dual-lane-captions) | Speech/listening captions, expiry and replay rejection, with a browser demo |
| [VRM Avatar Polish Loop](https://github.com/Star-957/vrm-avatar-polish-loop) | Agent workflow skills for Blender/MMD inspection, SpringBone tuning and visual QA |

A machine-readable index of this page lives in [`catalog.json`](https://github.com/Star-957/Star-957/blob/main/catalog.json).

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg" alt="" width="100%">
  </picture>
</p>

## 🛠 Toolbox

<p align="center">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white">
  <br>
  <img alt="three.js" src="https://img.shields.io/badge/three.js-000000?style=flat-square&logo=threedotjs&logoColor=white">
  <img alt="Blender" src="https://img.shields.io/badge/Blender-F5792A?style=flat-square&logo=blender&logoColor=white">
  <img alt="Electron" src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white">
  <img alt="ffmpeg" src="https://img.shields.io/badge/ffmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white">
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white">
  <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
</p>

## 📈 Public work, at a glance

| Signal | Value |
| --- | --- |
| Public repositories | **13** |
| Offline regression checks in the video evidence toolkit alone | **144** |
| Deterministic test suites (geometry + Monte Carlo) | **3 repos** |
| Report languages | English · 繁體中文 |
| Banner, section rules, language chart | Hand-written SVG committed in this repo (the small shields.io badges are the one third-party visual) |

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/langs-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/langs-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/langs-light.svg" alt="Language mix across public repositories: Python 51.16%, JavaScript 28.28%, TypeScript 18.33%, CSS 1.08%, HTML 0.71%, PowerShell 0.34%, Batchfile 0.12%" width="100%">
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg">
    <img src="https://raw.githubusercontent.com/Star-957/Star-957/main/assets/rule-light.svg" alt="" width="100%">
  </picture>
</p>

## 📖 Reading the evidence

Tests establish the documented cases, not universal safety, visual acceptance or production readiness.
Public reports are dated research snapshots; follow their source links and stated limitations. Tool
mentions are not endorsements. Check each repository's own licence and third-party notices before
reuse: public visibility alone does not grant a blanket licence.

This is a curated index of public work, checked on **2026-10-25**. It contains no private-project
directory, personal records, credentials, original artwork or raw conversations.
