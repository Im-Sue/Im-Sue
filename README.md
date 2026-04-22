<h1 align="center">Hi, I'm Sue 👋</h1>

<p align="center">
  <b>Senior Java Engineer · Tech Lead · Creator of SU-CCB Framework</b><br/>
  <sub>7+ yrs backend engineering · 3 yrs leading teams · PMP certified</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/🟢_Open_to-AI_Agent_Architect_/_AI_Application_Lead-2ea44f?style=for-the-badge"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-7%2B%20yrs-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Role-Tech%20Lead-0A66C2?style=flat-square"/>
  <img src="https://img.shields.io/badge/AI_Agent_Platform-Production-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/SU--CCB-Framework_Author-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/PMP-Certified-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Base-Guangzhou-1f6feb?style=flat-square"/>
</p>

---

### 👋 About Me

> I build AI Agent platforms **for** enterprises, and I build **tooling for the agents** that build them.

- 🏗 **Creator of [SU-CCB](https://github.com/SU-CCB)** — An open-source Claude + Codex multi-AI collaboration framework that treats AI collaboration as an **engineering management problem**, not "smart autocomplete"
- 🤖 **AI Agent Platform Tech Lead** — Leading a production multi-scenario Agent platform (LangChain · Workflow · Multi-tool orchestration · Runtime governance) for customer service and operations
- 🧱 **7+ yrs solid Java backend** — Spring Boot / Spring Cloud / Spring Security across SaaS, government platforms, IoT systems
- 👥 **3 yrs leading dev teams** — 0→1 tech stack building · architecture decisions · cross-functional coordination · PMP certified
- 🏭 **Delivered in the wild** — Guangzhou municipal platform · university IoT deployment · enterprise AI Agent platform
- 🧪 **Side quests** — Web3 × AI intersection (Solana · Sui · Solidity · ZK)

---

### 🎯 Featured: SU-CCB Framework

<p>
  <a href="https://github.com/SU-CCB/su-ccb-claude-plugin">
    <img src="https://img.shields.io/badge/SU--CCB-Claude_Plugin-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  </a>
  <a href="https://github.com/SU-CCB/su-ccb-codex-skills">
    <img src="https://img.shields.io/badge/SU--CCB-Codex_Skills-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  </a>
</p>

**SU-CCB** (Claude + Codex Collaboration Framework) establishes design-execution separation, approval gates, multi-round consultation, and structured contracts between Claude and Codex — turning multi-AI coding from a vibe into a disciplined engineering workflow.

```
User → /su:plan → Claude designs + consults Codex → /su:dispatch → Codex executes
                                                                        │
User ← /su:archive ← Claude reviews ← completion hook ← receipt ────────┘
```

**Core principles** — Role Separation · Approval Gates (Red/Yellow/Green) · Multi-Round Consultation · Structured Contracts (Ask / Receipt / Consult / Bounceback) · Graceful Degradation

**Install**:
```bash
/plugin marketplace add SU-CCB/su-ccb-claude-plugin
/plugin install ccb@SU-CCB
```

Built on top of [bfly123/claude_code_bridge](https://github.com/bfly123/claude_code_bridge), with optional integration of [SuperClaude](https://github.com/SuperClaude-Org/SuperClaude_Framework) and [Superpowers](https://github.com/obra/superpowers).

---

### 🛠 Tech Stack

**Backend Core**
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Data & Middleware**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![RocketMQ](https://img.shields.io/badge/RocketMQ-D77310?style=flat&logo=apache&logoColor=white)
![TDengine](https://img.shields.io/badge/TDengine-FF0F00?style=flat)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white)

**AI / Agent Engineering**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![ComfyUI](https://img.shields.io/badge/ComfyUI-000?style=flat)

**DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![SkyWalking](https://img.shields.io/badge/SkyWalking-FC7B03?style=flat&logo=apache&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![ELK](https://img.shields.io/badge/ELK-005571?style=flat&logo=elasticsearch&logoColor=white)

---

### 🏗 What I've Built at Work

> Production-grade projects I led. Source lives in corporate repos — this is the architectural track record.

| Project | Role | Stack | Impact |
|---|---|---|---|
| 🤖 **多场景 AI Agent 平台** `2025.08–Now` | Tech Lead | Spring Boot · LangChain · Workflow · RocketMQ | Unified Agent onboarding, task orchestration & runtime governance for customer-service + operations business lines |
| 🏫 **智慧室内控制系统** `2024.09–2025.06` | Dev Lead / PM | Spring Boot · MQTT · TDengine · Redis | Deployed in 20 classrooms, 99% device uptime, projected 20%+ electricity savings, software copyright obtained |
| 🏗 **穗建市级劳务平台** `2021.03–2024.07` | Dev Lead | Spring Cloud · RocketMQ · SkyWalking · Docker | Guangzhou municipal labor platform, serving 100+ construction sites |
| 🌐 **凡科网 SaaS 平台** `2018.07–2021.03` | Java Engineer | Spring MVC · Payment / Auth / Cross-lang | 3× S-grade performance · 1× employee of the year |

---

### 🌟 Open-Source Projects

- 🔥 **[SU-CCB/su-ccb-claude-plugin](https://github.com/SU-CCB/su-ccb-claude-plugin)** `Shell` — Claude Code Plugin with `/su:*` commands
- 🧩 **[SU-CCB/su-ccb-codex-skills](https://github.com/SU-CCB/su-ccb-codex-skills)** `Shell` — Codex Skill Pack with structured contracts
- 🎙 **[realtime_translator](https://github.com/Im-Sue/realtime_translator)** `Python` `44⭐` — Real-time Chinese↔English meeting interpreter
- 💎 **[Pelago](https://github.com/Im-Sue/Pelago)** `TypeScript` — Next-Gen Isolated Lending Protocol on Solana
- 🗳 **[ZKVote](https://github.com/Im-Sue/ZKVote)** `Solidity` — Anonymous voting contract based on ZK
- 🔥 **[campfire_hackathon](https://github.com/Im-Sue/campfire_hackathon)** `Java` — Monad prediction market hackathon

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Im-Sue&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Im-Sue&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="165" />
</p>

---

### 📫 Let's Talk

<table>
<tr><td><b>🟢 Open to roles</b></td><td>AI Agent Architect · AI Application Lead · Senior Java (AI-oriented) · Tech Lead</td></tr>
<tr><td><b>📍 Location</b></td><td>Guangzhou · open to Guangzhou / Shenzhen</td></tr>
<tr><td><b>💬 Telegram</b></td><td>@Sue_muyu</td></tr>
<tr><td><b>🏷 Keywords</b></td><td>AI Agent Platform · LangChain · SU-CCB · Spring Cloud · Production-grade</td></tr>
</table>

<p align="center"><sub><i>Building AI platforms · Engineering the agents that build them · Always learning</i></sub></p>
