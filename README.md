<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/hrygo/hrygo/main/header.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/hrygo/hrygo/main/header.svg">
    <img alt="黄飞虹 — AI Infrastructure Architect" src="https://raw.githubusercontent.com/hrygo/hrygo/main/header.svg" width="100%">
  </picture>
</div>

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/AI%20Infrastructure%20Architect-9556d7?style=for-the-badge&logo=github&logoColor=white" alt="AI Infrastructure Architect">
  <img src="https://img.shields.io/badge/Agent%20Infra%20%C2%B7%20Real--time%20Speech%20%C2%B7%20Local--First-008289?style=for-the-badge" alt="Agent Infra · Real-time Speech · Local-First">
</p>

<br/>

> **"Intelligence is non-deterministic. Infrastructure shouldn't be."**
>
> — Architecting the boundary between non-deterministic AI and highly-reliable systems.

<br/>

### `[ ARCHITECTURE MATRIX ] // 核心工程矩阵`

#### 🌐 1. AI Agent Orchestration, Workspaces & Gateway

<table>
  <tr>
    <td width="30%">⟐ <a href="https://github.com/hrygo/hotplex"><b>HotPlex</b></a><br><sub>Unified Access Layer for AI Coding Agents</sub></td>
    <td width="15%"><img src="https://img.shields.io/badge/Go-0081a2?style=flat-square&logo=go&logoColor=white" alt="Go"><br><sub>Apache-2.0</sub></td>
    <td width="20%"><img src="https://img.shields.io/github/stars/hrygo/hotplex?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td width="20%"><img src="https://img.shields.io/github/last-commit/hrygo/hotplex?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td width="15%"><a href="https://github.com/hrygo/hotplex"><img src="https://img.shields.io/badge/Flagship-9556d7?style=flat-square" alt="Flagship"></a></td>
  </tr>
  <tr>
    <td colspan="5">
      高并发、基于 WebSocket 的 Agent 统一接入与路由层。打通本地自主 Worker（Claude Code、OpenCode）与企业 IM（Slack、飞书），具备多模型动态路由、自愈重试与零停机编排能力。
    </td>
  </tr>
  <tr>
    <td>💼 <a href="https://github.com/hrygo/Delegra"><b>Delegra</b></a><br><sub>Agent Management & Collaboration Workspace</sub></td>
    <td><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"></td>
    <td><img src="https://img.shields.io/github/stars/hrygo/Delegra?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td><img src="https://img.shields.io/github/last-commit/hrygo/Delegra?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td><sub>Workspace</sub></td>
  </tr>
  <tr>
    <td colspan="5">
      面向实际工作场景的开源多 Agent 管理与协同工作台：组织、调度并委派 AI Agent 执行团队级实际工作任务。
    </td>
  </tr>
  <tr>
    <td>⚙️ <a href="https://github.com/hrygo/heluo-forge"><b>heluo-forge</b></a><br><sub>Enterprise Agentic Engineering Platform</sub></td>
    <td><img src="https://img.shields.io/badge/Enterprise-24292f?style=flat-square" alt="Enterprise"></td>
    <td><img src="https://img.shields.io/github/stars/hrygo/heluo-forge?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td><img src="https://img.shields.io/github/last-commit/hrygo/heluo-forge?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td><sub>Platform</sub></td>
  </tr>
  <tr>
    <td colspan="5">
      企业级智能研发平台方案与 Agentic Workflows 落地扩展工程。
    </td>
  </tr>
  <tr>
    <td>🎬 <a href="https://github.com/hrygo/clawreel"><b>ClawReel</b></a><br><sub>Autonomous Pipeline with HITL Governance</sub></td>
    <td><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"></td>
    <td><img src="https://img.shields.io/github/stars/hrygo/clawreel?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td><img src="https://img.shields.io/github/last-commit/hrygo/clawreel?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td><sub>Automation</sub></td>
  </tr>
  <tr>
    <td colspan="5">
      Agent 驱动的全流程自动化流水线，集成 Human-in-the-Loop (HITL) 决策检查点与算力成本治理。
    </td>
  </tr>
</table>

<br/>

#### 🎙️ 2. Speech Infrastructure (Cloud Cluster & Local-First Dual Runtimes)

<table>
  <tr>
    <td width="30%">⚡ <a href="https://github.com/hrygo/SpeechNexus"><b>SpeechNexus</b></a><br><sub>Enterprise Distributed Speech Platform</sub></td>
    <td width="15%"><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"><br><sub>vLLM / Omni</sub></td>
    <td width="20%"><img src="https://img.shields.io/github/stars/hrygo/SpeechNexus?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td width="20%"><img src="https://img.shields.io/github/last-commit/hrygo/SpeechNexus?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td width="15%"><sub>Server Cluster</sub></td>
  </tr>
  <tr>
    <td colspan="5">
      基于 <b>vLLM</b> 与 <b>vLLM-Omni</b> 构建的企业级全双工实时/离线语音底座。高吞吐并发调度、低延迟声学推理与一体化管理控制面。
    </td>
  </tr>
  <tr>
    <td>🍎 <a href="https://github.com/hrygo/SpeechRail"><b>SpeechRail</b></a><br><sub>Local-First ASR/TTS Engine (Apple Silicon)</sub></td>
    <td><img src="https://img.shields.io/badge/Swift%20%7C%20Py-d04630?style=flat-square&logo=swift&logoColor=white" alt="Swift"></td>
    <td><img src="https://img.shields.io/github/stars/hrygo/SpeechRail?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td><img src="https://img.shields.io/github/last-commit/hrygo/SpeechRail?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td><sub>Edge / macOS</sub></td>
  </tr>
  <tr>
    <td colspan="5">
      专为 Apple Silicon (MLX) 深度优化的单机高可用语音服务。提供 OpenAI 兼容的 REST / Realtime WebSocket 协议，单机原生集成与微秒级治理。
    </td>
  </tr>
  <tr>
    <td>🔌 <a href="https://github.com/hrygo/dsh-speechrail-bundle"><b>dsh-speechrail-bundle</b></a><br><sub>Voice-Input Agent Integration Suite</sub></td>
    <td><img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TS"></td>
    <td><img src="https://img.shields.io/github/stars/hrygo/dsh-speechrail-bundle?style=flat-square&label=Stars&color=58a6ff" alt="Stars"></td>
    <td><img src="https://img.shields.io/github/last-commit/hrygo/dsh-speechrail-bundle?style=flat-square&label=Last%20Active&color=9556d7" alt="Last Active"></td>
    <td><sub>Agent Tooling</sub></td>
  </tr>
  <tr>
    <td colspan="5">
      针对 Agent 交互环境设计的语音接入套件：打通浏览器采集与本地语音运行时，提供状态快照与原子级凭据治理。
    </td>
  </tr>
</table>

<br/>

#### 🕯️ 3. Generative Systems & Autonomous Applications

- 🕯️ **[WorldofMysteries](https://github.com/hrygo/WorldofMysteries)** <img src="https://img.shields.io/github/stars/hrygo/WorldofMysteries?style=flat-square&label=Stars&color=58a6ff"> <img src="https://img.shields.io/github/last-commit/hrygo/WorldofMysteries?style=flat-square&label=Last%20Active&color=9556d7"><br>
  《诡秘世界》AI 互动叙事系统 —— “世界不会重置，角色不会失忆”。维多利亚蒸汽朋克 × 克苏鲁神秘学。SwiftUI 原生客户端 + 状态机演化机制 + 本地端侧 LLM 运行时。
- 🃏 **[lotm-card-art](https://github.com/hrygo/lotm-card-art)** <img src="https://img.shields.io/github/stars/hrygo/lotm-card-art?style=flat-square&label=Stars&color=58a6ff"><br>
  生成式艺术制作脚手架：将提示词与生图管线转化为确定性、可版本复现的代码构建产物。

<br/>

### `[ STACK ] // Technical Arsenal`

<div align="center">
  <img src="https://skillicons.dev/icons?i=go,python,swift,c,ts,docker,apple,linux,git,github,fastapi,redis" alt="技术栈" width="460">
</div>

<details>
<summary><b>技术栈与核心聚焦</b></summary>

```text
LANGUAGES       Go · Python · Swift · C · TypeScript · Shell
DOMAINS         AI Agent Infra · LLM Gateways · Multimodal Systems · Speech / Audio Runtimes
PROTOCOLS       Model Context Protocol (MCP) · Agent Exchange Protocol (AEP) · WebSocket · OpenAI Realtime
INFRASTRUCTURE  Apple Silicon (MLX) · vLLM · Docker · Traefik · Redis · Systemd / Launchd
CORE FOCUS      Fault Tolerance · Backpressure Management · Finite State Machines · Zero-Downtime
```

</details>

<br/>

### `[ ARCHIVE & SUPPORTING ] // 更多工程与沉淀`

<details>
<summary><b>展开查看更多项目 (10+)</b></summary>

[![gosms](https://img.shields.io/badge/gosms-51%E2%98%85-008289?style=flat-square&logo=go&logoColor=white)](https://github.com/hrygo/gosms) · [Hikmah](https://github.com/hrygo/hikmah) · [ImageHive](https://github.com/hrygo/ImageHive) · [SparkForge](https://github.com/hrygo/SparkForge) · [The Council](https://github.com/hrygo/council) · [openclaw-watchdog](https://github.com/hrygo/openclaw-watchdog) · [security-shield](https://github.com/hrygo/security-shield) · [SpecBuilder](https://github.com/hrygo/SpecBuilder) · [Sona](https://github.com/hrygo/sona) · [echomind](https://github.com/hrygo/echomind) · [phantom-stream](https://github.com/hrygo/phantom-stream) · [obsidian-skills](https://github.com/hrygo/obsidian-skills)

</details>

<br/>

### `[ TELEMETRY ] // System Metrics`

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=hrygo&show_icons=true&hide_border=true&bg_color=0d1117&title_color=b066fe&icon_color=00f2fe&text_color=8b949e&text_bold=false">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=hrygo&show_icons=true&hide_border=true&bg_color=ffffff&title_color=4f46e5&icon_color=0969da&text_color=57606a&text_bold=false">
    <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=hrygo&show_icons=true&hide_border=true&bg_color=0d1117&title_color=b066fe&icon_color=00f2fe&text_color=8b949e&text_bold=false" width="48%">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=hrygo&layout=compact&hide_border=true&bg_color=0d1117&title_color=b066fe&text_color=8b949e&langs_count=8">
    <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=hrygo&layout=compact&hide_border=true&bg_color=ffffff&title_color=4f46e5&text_color=57606a&langs_count=8">
    <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hrygo&layout=compact&hide_border=true&bg_color=0d1117&title_color=b066fe&text_color=8b949e&langs_count=8" width="48%">
  </picture>
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=hrygo&background=00000000&border=00000000&ring=b066fe&fire=00f2fe&currStreakLabel=8b949e&sideLabels=8b949e&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff">
    <source media="(prefers-color-scheme: light)" srcset="https://streak-stats.demolab.com?user=hrygo&background=00000000&border=00000000&ring=6366f1&fire=0969da&currStreakLabel=57606a&sideLabels=57606a&dates=57606a&currStreakNum=24292f&sideNums=24292f">
    <img alt="GitHub Streak" src="https://streak-stats.demolab.com?user=hrygo&background=00000000&border=00000000&ring=b066fe&fire=00f2fe">
  </picture>
</div>

<br/>

### `[ HANDSHAKE ] // Connect & Collaborate`

<div align="center">

[![Email](https://img.shields.io/badge/Email-aaronwong1989%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:aaronwong1989@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-hrygo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hrygo)

<br/>

<sub><i>Reliability is the absence of surprise. Open for AI Infra architecture discussions and high-performance system collaborations.</i></sub>

</div>

<br/>

<div align="right">
  <sub>
    <img src="https://komarev.com/ghpvc/?username=hrygo&color=58a6ff&style=flat-square&label=visitors" alt="Profile Views">
  </sub>
</div>
