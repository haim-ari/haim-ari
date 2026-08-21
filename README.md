<div align="center">

<a href="https://dkod.ai">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=30&duration=2500&pause=1000&color=06B6D4&center=true&vCenter=true&repeat=false&width=650&height=45&lines=Haim+Ari" alt="Name" />
  <br>
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=18&duration=2000&pause=1000000&color=9CA3AF&center=true&vCenter=true&repeat=false&delay=2800&width=650&height=30&lines=Building+the+governed+build+pipeline+for+AI-built+apps" alt="Tagline" />
</a>

<br>

<sub>Platform Engineer &bull; Open Source &bull; Israel</sub>

<br>
<br>

<a href="https://linkedin.com/in/haimari"><img src="https://img.shields.io/badge/LinkedIn-haimari-06b6d4?style=for-the-badge&labelColor=0f0f14&logo=linkedin&logoColor=06b6d4" alt="LinkedIn"></a>&nbsp;
<a href="https://twitter.com/dkod_ai"><img src="https://img.shields.io/badge/X-@dkod__ai-06b6d4?style=for-the-badge&labelColor=0f0f14&logo=x&logoColor=06b6d4" alt="X"></a>&nbsp;
<a href="https://vantageacademy.io"><img src="https://img.shields.io/badge/Blog-Vantage_Academy-06b6d4?style=for-the-badge&labelColor=0f0f14&logo=hashnode&logoColor=06b6d4" alt="Blog"></a>

</div>

<br>

## What I'm Building

**[dkod](https://dkod.ai)** — the governed build pipeline for AI-built internal apps.

Across organizations, employees are vibe-coding internal tools that ship with no git, no auth, and secrets sitting in `.env` files. IT cannot see them, so IT cannot govern them. DKOD finds those apps, scores the risk, and rebuilds the ones that qualify from approved templates, in your own cloud.

Three parts. Find the apps first, then rebuild the ones worth keeping.

&bull;&nbsp; **dkod-signals** — one static Rust binary, pushed by MDM to every macOS, Windows and Linux device. It runs once at low priority, inventories the apps built by Claude Code, Codex, Cursor and other agents, scores each for risk, and writes one metrics-only JSON report. It never uploads, never phones home, and never executes what it finds. *Available today.*<br>
&bull;&nbsp; **Aggregation and reporting** — rolls the per-device reports into an org-wide picture of AI-app risk. *Coming.*<br>
&bull;&nbsp; **The governed build pipeline** — rebuilds qualifying apps from hardened templates, with deterministic gates and human approval by risk tier. Anything outside the envelope gets a named blocker instead of a silent skip. *Early access.*

Nothing leaves your infrastructure without consent. Metrics-only by default.

<a href="https://dkod.ai"><img src="https://img.shields.io/badge/dkod.ai-website-06b6d4?style=flat-square&labelColor=0f0f14" alt="Website"></a>&nbsp;
<a href="https://dkod.ai/download"><img src="https://img.shields.io/badge/dkod--signals-available_today-06b6d4?style=flat-square&labelColor=0f0f14" alt="dkod-signals"></a>&nbsp;
<a href="https://dkod.ai/blog"><img src="https://img.shields.io/badge/blog-AI_app_governance-06b6d4?style=flat-square&labelColor=0f0f14" alt="Blog"></a>

---

## Background

15+ years building platforms at scale — AdTech, cloud infrastructure, Kubernetes, CI/CD, and high-throughput data pipelines. Currently at **[Start.io](https://start.io)**.

Rewrote a production Java platform in Rust in 2.5 days, with AI doing the coding autonomously. What stuck with me afterwards was not the speed. It was realising how much software gets built this way now, by people who are not engineers, with nothing checking it and nobody keeping a list. That is what DKOD is for.

---

## Tech

<div align="center">

<table>
<tr>
<td align="center" width="110"><b>Languages</b></td>
<td>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=rust,ts,go,py&theme=dark" alt="Languages" /></a>
</td>
</tr>
<tr>
<td align="center" width="110"><b>Infra</b></td>
<td>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=kubernetes,docker,aws,terraform&theme=dark" alt="Infrastructure" /></a>
</td>
</tr>
<tr>
<td align="center" width="110"><b>Data</b></td>
<td>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=postgres,redis,graphql,kafka&theme=dark" alt="Data" /></a>
</td>
</tr>
<tr>
<td align="center" width="110"><b>Frontend</b></td>
<td>
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=react,vite,tailwind,html&theme=dark" alt="Frontend" /></a>
</td>
</tr>
</table>

</div>

---

## Writing

I write about AI-assisted engineering, platform architecture, and building with AI agents at scale.

&bull;&nbsp; **[Vantage Academy](https://vantageacademy.io)** — AI engineering blog<br>
&bull;&nbsp; **[dkod Blog](https://dkod.ai/blog)** — AI-app governance and the agentic SDLC

---

<div align="center">

<a href="https://github.com/haim-ari">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=haim-ari&theme=transparent&hide_border=true&ring=06b6d4&fire=06b6d4&currStreakLabel=06b6d4&sideLabels=9ca3af&currStreakNum=f0f0f3&sideNums=f0f0f3&dates=4a4a5a&background=0f0f14" height="180" alt="GitHub Streak" />
</a>

<br>
<br>

<sub>Building infrastructure for the age of AI agents &bull; <a href="https://dkod.ai">dkod.ai</a></sub>

</div>