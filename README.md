<div align="center">

<!-- Capsule Render Banner -->
![header](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2744,100:0d1117&height=200&section=header&text=Myrkh&fontSize=72&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=Functional%20Safety%20Engineer%20%7C%20Open-Source%20Builder&descAlignY=58&descSize=18&descColor=8b949e)

<!-- Typing SVG -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Building+open+tools+for+IEC+61508+SIL+calculations;Python+%7C+TypeScript+%7C+Markov+CTMC;Making+safety+engineering+transparent+%26+auditable)](https://git.io/typing-svg)

</div>

---

## 🛡️ About me

I build **open-source tools for functional safety** — the kind of software that verifies whether a safety system will actually work before someone's life depends on it.

Currently working on **[PRISM / sil-engine](https://github.com/Myrkh/PRISM_SIL_ENGINE)** — the first fully transparent, auditable alternative to closed commercial tools like GRIF, exSILentia, and SILSafer.

> *Every formula traceable. Every result reproducible. No black boxes.*

```python
from sil_engine import SubsystemParams, pfd_arch, sil_achieved

p = SubsystemParams(lambda_DU=5e-8, DC=0.9, beta=0.02, T1=8760.0)
pfd = pfd_arch(p, "1oo2")   # → 4.48e-06  ✅ SIL 4
```

---

## 🔧 Stack

<div align="center">

![Python](https://img.shields.io/badge/Python_3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_5-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

</div>

**Domain:** IEC 61508 · Markov CTMC · Reliability Engineering · SIL / SIF / SIS  
**Methods:** Analytical PFD/PFH · Exact matrix exponential · Monte Carlo · CCF (β-factor, MGL)

---

## 📌 Featured project

### ⚙️ [PRISM / sil-engine](https://github.com/Myrkh/PRISM_SIL_ENGINE)

> Open-source IEC 61508 SIL calculation engine — analytical + exact Markov CTMC

| | |
|---|---|
| 🎯 **What it does** | Computes PFDavg & PFH for any kooN architecture, with full architectural constraint checks (SFF, HFT, Route 1H/2H) |
| ✅ **Validated against** | IEC 61508-6 Tables B.2–B.13 · 61508.org worked examples · NTNU Markov examples |
| 📦 **Install** | `pip install sil-engine` · `npm install @sil-engine/ts` |
| 📄 **License** | LGPL v3 — free for commercial use, modifications must stay open |

[![License: LGPL v3](https://img.shields.io/badge/License-LGPL_v3-blue.svg)](https://github.com/Myrkh/PRISM_SIL_ENGINE/blob/main/LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://python.org)
[![Validated](https://img.shields.io/badge/IEC_61508--6_79%20test_cases-green.svg)](https://github.com/Myrkh/PRISM_SIL_ENGINE/blob/main/packages/sil-py/tests)
[![CI](https://github.com/Myrkh/PRISM_SIL_ENGINE/actions/workflows/ci.yml/badge.svg)](https://github.com/Myrkh/PRISM_SIL_ENGINE/actions)

---

## 📊 GitHub stats

<div align="center">

![Myrkh's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Myrkh&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Myrkh&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Myrkh&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=1a2744&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)

</div>

---

## 💬 Wanted contributions

If you work in functional safety and have access to:

- 📄 Omeiri/Innal 2021 — corrected PFH 1oo2 formula
- 📄 Innal/Lundteigen 2016 RESS — PST with 3 distinct repair times
- 🖥️ Benchmark outputs from GRIF or exSILentia (screenshots welcome)

→ Open an issue or a PR. The community thanks you.

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a2744,100:0d1117&height=100&section=footer)

*Safety is too important to be a black box.*

</div>
