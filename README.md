![banner](banner.svg)

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&pause=1200&color=1d9e75&center=true&vCenter=true&width=550&lines=Building+open-source+tools+for+functional+safety;IEC+61508+%7C+SIL+%7C+SIF+%7C+LOPA;From+the+design+office+to+the+control+room)](https://git.io/typing-svg)

</div>

---

## 👤 About me

I'm a process control and functional safety engineer — and a fullstack developer in my spare time.
That combination is what makes PRISM possible: I know exactly what's broken in the industry, and I can build the fix myself. I'm developing a suite of products under the PRISM name — from SIL calculation to live monitoring in control rooms.

I build open-source tools for functional safety and I'm developing a suite of products under the **PRISM** name — from SIL calculation to live monitoring in control rooms.

---

## 🔧 What I'm building

### 📐 .sil — A language for functional safety *(invented)*

I designed **`.sil`**, a domain-specific language that lets engineers write LOPA and SIF specifications as structured, versionable code — from hazard identification all the way to a fully compliant IEC 61511 Safety Instrumented Function.

> 📄 See a real example: [SIF-001.sil](https://github.com/Myrkh/Myrkh/blob/main/SIF-001.sil)

- **VSCode extension** — syntax highlighting, hover, diagnostics, IEC compliance checks inline
- **Live UI preview** — designers see the SIF graphically as they type, no separate tool needed
- **Full lifecycle in one file** — LOPA → SIL target → SIF design → proof test schedule
- **Git-native** — diff your safety specs, review changes, track history like real engineering

> A `.sil` file is more auditable than any Excel sheet and more transparent than PHA-Pro or exSILentia.

---

### ⚙️ [sil-engine](https://github.com/Myrkh/PRISM_SIL_ENGINE)

Open-source SIL calculation engine. The auditable core that powers everything else.

![Python](https://img.shields.io/badge/Python_3.10+-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_5-007ACC?style=flat-square&logo=typescript&logoColor=white)
![License LGPL](https://img.shields.io/badge/License-LGPL_v3-blue?style=flat-square)
![IEC 61508](https://img.shields.io/badge/IEC_61508-Validated-1d9e75?style=flat-square)
[![CI](https://github.com/Myrkh/PRISM_SIL_ENGINE/actions/workflows/ci.yml/badge.svg)](https://github.com/Myrkh/PRISM_SIL_ENGINE/actions)

---

### 🧠 PRISM *(in development)*

Full lifecycle platform for Safety Instrumented Systems — from LOPA to SIF.

![Status](https://img.shields.io/badge/Status-In_Development-orange?style=flat-square)
![Standard](https://img.shields.io/badge/IEC_61511-blue?style=flat-square)

- **LOPA designer** — structured layer of protection analysis
- **SIF designer** — design your Safety Instrumented Functions
- **Component library** — reusable, traceable safety components
- **Test procedures** — manage proof tests and inspection records
- **Lifecycle tracking** — LOPA → SIF → operation, end-to-end

---

### 🏭 PRISM Operations *(in development)*

Built to live in **control rooms**.

![Status](https://img.shields.io/badge/Status-In_Development-orange?style=flat-square)
![OPC-UA](https://img.shields.io/badge/OPC--UA-Connected-0f6e56?style=flat-square)
![SIL Live](https://img.shields.io/badge/SIL-Live_Monitoring-1d9e75?style=flat-square)

Connected via **OPC-UA** to monitor SIL performance in real time — live diagnostic coverage, demand rates, PFD tracking. Safety that doesn't stop at the design office.

---
