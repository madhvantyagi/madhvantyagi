<div align="center">

<!-- ════════════════  HERO ════════════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,55:2563eb,100:c084fc&height=200&section=header&text=Madhvan%20Tyagi&fontSize=58&fontColor=E6EDF3&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20Full%2DStack%20%C2%B7%20ML%20Research&descSize=17&descColor=60a5fa&descAlignY=60&descAlign=50" width="100%" alt="Madhvan Tyagi" />

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=2800&pause=900&color=60a5fa&center=true&vCenter=true&width=720&lines=training+SLMs+from+scratch%2C+token+by+token;reverse-engineering+transformer+internals;understanding+the+math+behind+attention;building+eval+loops+models+can't+cheat+on;steering+agent+behavior+without+retraining;shipping+research+systems+that+beat+frontier+baselines" alt="Typing intro" width="720" />

<br/>

<!-- socials — brand colors kept natural -->
<a href="https://www.linkedin.com/in/madhvan-tyagi-10a44a222/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:madhvantyagi1@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://leetcode.com/Madhvan/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
<a href="https://github.com/madhvantyagi"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
<a href="https://www.wort.nyc"><img src="https://img.shields.io/badge/WORT.nyc-c084fc?style=for-the-badge&logo=googlechrome&logoColor=black" alt="WORT" /></a>

<br/><br/>

<!-- vitals ribbon — clean single line -->
<img src="https://img.shields.io/badge/📍-Jersey%20City%2C%20NJ-60a5fa?style=flat-square&label=Location&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Status-Open%20to%20Work-60a5fa?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Experience-2.5%2B%20Years-60a5fa?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/LeetCode-300%2B-c084fc?style=flat-square&labelColor=0D1117" />

</div>

---

## About

> I build AI systems that ship in production, not notebooks. Computer Science at **Queens College, CUNY** (May 2026). I work across RLVR fine-tuning, multi-agent orchestration, hybrid retrieval, and backend infrastructure serving thousands of users.

When a problem needs custom architecture instead of a prompt tweak, that is where I do my best work. I founded **[WORT.AI](https://www.wort.nyc)** and **[SOUL.md](https://github.com/madhvantyagi/SOUL.md)**.

<p align="center">
<img src="https://img.shields.io/badge/Focus-AI_Agents-c084fc?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Focus-LLM_Systems-60a5fa?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Focus-Production_ML-60a5fa?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Focus-Backend_Arch-c084fc?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Focus-RLVR_FineTuning-60a5fa?style=flat-square&labelColor=0D1117" />
</p>

---

## Featured Projects

### WORT.AI · Autonomous Deep Research Agent
*Recursive BFS · parallel researcher–reviewer loops · cited HTML reports · hybrid RAG memory*

<p align="center">
<a href="https://github.com/wortai/deep-research-agent"><img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white" alt="Repo" /></a>
<a href="https://www.wort.nyc"><img src="https://img.shields.io/badge/Live_Demo-60a5fa?style=flat-square&logo=googlechrome&logoColor=black" alt="Live" /></a>
<img src="https://img.shields.io/github/stars/wortai/deep-research-agent?style=flat-square&logo=github&label=Stars&color=60a5fa&labelColor=0D1117" />
<img src="https://img.shields.io/github/forks/wortai/deep-research-agent?style=flat-square&logo=github&label=Forks&color=60a5fa&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Query_Gen-71%25%20%E2%86%92%2094%25-c084fc?style=flat-square&logo=probot&logoColor=black&label=RLVR+Eval&labelColor=0D1117" />
</p>

<p align="center">
<img src="https://img.shields.io/badge/GOAL-decompose-60a5fa?style=flat-square&labelColor=0D1117" />
&nbsp;<b>›</b>&nbsp;
<img src="https://img.shields.io/badge/PLAN-BFS%20tree-60a5fa?style=flat-square&labelColor=0D1117" />
&nbsp;<b>›</b>&nbsp;
<img src="https://img.shields.io/badge/RUN-parallel%20agents-60a5fa?style=flat-square&labelColor=0D1117" />
&nbsp;<b>›</b>&nbsp;
<img src="https://img.shields.io/badge/REVIEW-reroute-60a5fa?style=flat-square&labelColor=0D1117" />
&nbsp;<b>›</b>&nbsp;
<img src="https://img.shields.io/badge/SHIP-cited%20report-c084fc?style=flat-square&labelColor=0D1117" />
</p>

A research engine built from first principles. WORT decomposes a goal into sub-queries, runs parallel researcher–reviewer subgraphs, closes information gaps iteratively, and ships cited reports people can trust.

| Layer | Implementation |
| :-- | :-- |
| **Orchestration** | LangGraph state machine with human-in-the-loop checkpoints and dynamic parallel subgraphs |
| **Research** | BFS tree per agent; reviewer redirects weak paths in real time |
| **Memory** | Qdrant dense + sparse BM25, RRF fusion, cross-encoder reranking |
| **Training** | RLVR on Qwen for query generation (71% → 94%) and report synthesis |
| **Xtreme** | VM-backed code execution, messy web pages, richer artifact export |

---

### SOUL.md · Portable Agent Persona Specification
*Behavioral steering · multi-model TRAIT eval · open source · drop-in agent personalities*

<p align="center">
<a href="https://github.com/madhvantyagi/SOUL.md"><img src="https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github&logoColor=white" alt="Repo" /></a>
<img src="https://img.shields.io/github/stars/madhvantyagi/SOUL.md?style=flat-square&logo=github&label=Stars&color=c084fc&labelColor=0D1117" />
<img src="https://img.shields.io/github/forks/madhvantyagi/SOUL.md?style=flat-square&logo=github&label=Forks&color=c084fc&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Persona_Hold-~78%25-60a5fa?style=flat-square&logo=shield&logoColor=black&label=Adversarial&labelColor=0D1117" />
</p>

Open-source collection of portable `SOUL.md` files that give LLM agents a distinct, stable personality and steer how they reason, respond, and push back.

| Layer | Detail |
| :-- | :-- |
| **Format** | Markdown persona spec: traits, tone, boundaries, reasoning style |
| **Research** | Weak-to-strong jailbreaking; small models can steer larger aligned models past 99% misalignment |
| **Evaluation** | Tested across DeepSeek, Gemini, Claude; adversarial personas held up to ~78% |
| **Impact** | 200+ stars and 20+ forks within two weeks of launch |

---

## Experience

### Software Engineer — CareSphere  ·  *Aug 2024 – Dec 2025*
Architected the workforce platform for **5,000+ caregivers** — scheduling, payroll, and performance tracking at scale.
- Built **Agent ZOI** with tool use and self-RAG memory — ticket resolution from days to minutes, covering workload of 7 support staff
- **80% load reduction** on scheduling APIs via Redis, query restructuring, and Postgres indexing under 5,000+ concurrent sessions
- Shipped gamified performance and rewards pipelines driving measurable caregiver engagement

### Machine Learning Research Assistant — Queens College, CUNY  ·  *Sep 2024 – Jan 2025*
Led a 4-person team on **LLMs for tabular data**.
- **90–93% classification** and **81–86% regression** — ~40 points above traditional ML baselines
- Fine-tuning pipelines for GPT-3.5/4 with token-efficient table representations
- Turned 25+ papers into a reproducible experimental pipeline

### Software Developer Intern — Ingelt Board  ·  *Jun – Aug 2023*
Backend for an education platform serving **10,000+ students** — REST APIs, 45% latency reduction, CI/CD (4h → 30min), Docker/K8s on AWS.

---

## GitHub Activity

<p align="center">
<img src="https://img.shields.io/github/followers/madhvantyagi?label=Followers&style=flat-square&color=60a5fa&labelColor=0D1117&logo=github" />
<img src="https://img.shields.io/badge/dynamic/json?color=c084fc&label=Public%20Repos&query=$.public_repos&url=https://api.github.com%2Fusers%2Fmadhvantyagi&style=flat-square&labelColor=0D1117&logo=github" />
<img src="https://img.shields.io/github/stars/madhvantyagi/SOUL.md?label=SOUL.md%20Stars&style=flat-square&color=60a5fa&labelColor=0D1117&logo=github" />
<img src="https://img.shields.io/github/last-commit/madhvantyagi/SOUL.md?label=Last%20Commit&style=flat-square&color=c084fc&labelColor=0D1117&logo=git" />
</p>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=madhvantyagi&show_icons=true&theme=dark&hide_border=true&title_color=60a5fa&text_color=E6EDF3&icon_color=60a5fa&bg_color=0D1117&ring_color=60a5fa&border_radius=14" alt="GitHub Stats" width="48%" />
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=madhvantyagi&layout=compact&theme=dark&hide_border=true&title_color=60a5fa&text_color=E6EDF3&bg_color=0D1117&langs_count=6&border_radius=14&hide=html,css,scss" alt="Top Languages" width="48%" />
</p>

<p align="center">
<img src="https://streak-stats.demolab.com/?user=madhvantyagi&theme=dark&hide_border=true&ring=60a5fa&fire=c084fc&currStreakLabel=60a5fa&sideLabels=E6EDF3&dates=8B949E&background=0D1117&border_radius=14" alt="GitHub Streak" width="100%" />
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=madhvantyagi&theme=react-dark&hide_border=true&bg_color=0D1117&color=60a5fa&line=30363D&point=c084fc&area=true&area_color=21262D&radius=14" alt="Contribution Graph" width="100%" />
</p>

<!-- contribution snake — auto-generated daily by the Generate Snake workflow -->
<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/madhvantyagi/madhvantyagi/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/madhvantyagi/madhvantyagi/output/github-snake.svg" />
  <img alt="github contribution snake" src="https://raw.githubusercontent.com/madhvantyagi/madhvantyagi/output/github-snake-dark.svg" width="100%" />
</picture>
</p>

---

<div align="center">

## Let's Build the Hard Stuff

Looking for teams building agent architectures, custom training pipelines, production RAG,<br/>and infrastructure that serves real users at scale.

<br/>

<a href="mailto:madhvantyagi1@gmail.com"><img src="https://img.shields.io/badge/Reach_Out-madhvantyagi1@gmail.com-60a5fa?style=for-the-badge&logo=gmail&logoColor=black" alt="Email" /></a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=madhvantyagi&color=60a5fa&style=for-the-badge&label=Profile%20Views&labelColor=0D1117" alt="Profile views" />

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:c084fc,45:2563eb,100:0D1117&height=90&section=footer&animation=twinkling&fontColor=E6EDF3&fontSize=1&text=%20" width="100%" alt="Footer" />

</div>
