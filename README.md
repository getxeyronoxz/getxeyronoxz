<div align="center">

# Xeyronox
### Systems Engineer & Cybersecurity Practitioner
**Specializing in Defensive Security · Local-First Architecture · High-Assurance Android & Desktop Tooling**

[![Available for Hire](https://img.shields.io/badge/Status-Available%20for%20Work%20%2F%20Contracts-10b981?style=flat-square&logo=github)](https://github.com/getxeyronoxz)
[![GitHub](https://img.shields.io/badge/GitHub-getxeyronoxz-1f2937?style=flat-square&logo=github&logoColor=white)](https://github.com/getxeyronoxz)
[![X](https://img.shields.io/badge/X-@xeyronox-1f2937?style=flat-square&logo=x&logoColor=white)](https://x.com/xeyronox)
[![Instagram](https://img.shields.io/badge/Instagram-@xeyronox-1f2937?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/xeyronox)

<br/>

<a href="https://github.com/getxeyronoxz">
  <img src="https://streak-stats.demolab.com/?user=getxeyronoxz&theme=dark&hide_border=true&background=0d1117&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8" alt="GitHub Activity & Contribution Stats" />
</a>

---

</div>

### 🎯 Core Capabilities for Engineering Teams

* **Low-Level Android & Systems Security:** Direct memory introspection (`AccessibilityNodeInfo`), hardware-backed crypto (Keystore / AES-256 GCM), SQLCipher, and 16 KB page alignment for Android 16/17.
* **Deterministic Financial & Data Engines:** Exact-decimal accounting engines (zero floating-point inaccuracies), atomic file persistence, and audit logging.
* **Signals & Intelligence Pipelines:** RF spectrum capture with RTL-SDR, cellular topology analysis (OpenCelliD/CellMapper), and graph-based correlation (NetworkX).
* **Local-First & Zero-Trust Architecture:** Systems designed with `0 INTERNET` network constraints, local AI harnesses, and strict privacy by design.

---

### ⚡ Shipped & Active Systems

#### 🛡️ [`local-upi-ledger`](https://github.com/getxeyronoxz/local-upi-ledger) &nbsp; `🟡 [In Active Deployment]`
*Zero-permission UPI transaction aggregator engineered for Android 16 & 17.*
- **Technical Highlight:** Completely omits `INTERNET` permission from manifest. Uses hardware-backed Android Keystore + SQLCipher 4.x.
- **Novel Solution:** Inspects in-memory accessibility trees to parse payment records past banking `FLAG_SECURE` screen restrictions without root.
- **Tech Stack:** `Kotlin` · `Jetpack Compose` · `SQLCipher` · `Room` · `AGPL-3.0`

#### ⚖️ [`open-merchant`](https://github.com/getxeyronoxz/open-merchant) &nbsp; `🟢 [Completed / v1.0.1]`
*AI-native, cross-platform desktop workbench for product economics & decision modeling.*
- **Technical Highlight:** Exact-decimal arithmetic engine (zero floating-point distortion) with atomic disk persistence.
- **Integration:** Features an air-gapped, read-only Model Context Protocol (`stdio MCP`) server for private agent reasoning.
- **Tech Stack:** `TypeScript` · `Electron` · `React` · `Zod` · `MCP` · `AGPL-3.0`

#### 📡 [`XGhostSignal`](https://github.com/getxeyronoxz/XGhostSignal) &nbsp; `🟢 [Completed / v0.2.0]`
*Local-first OSINT & cellular intelligence workbench.*
- **Technical Highlight:** Live RTL-SDR RF spectrum burst capture, cell-tower geospatial correlation, ADS-B flight tracking, and entity graphing.
- **Interface:** Dual high-speed CLI (`xgs`) and web console with local Ollama summarization.
- **Tech Stack:** `Python 3.9+` · `FastAPI` · `Typer` · `SQLAlchemy` · `PyRtlSdr` · `Scapy` · `MIT`

---

### 🔬 Active R&D & Engineering Focus

* **Systems Programming in Rust:** Building memory-safe, ultra-low overhead CLI tools and high-throughput pipelines.
* **Android 16/17 Platform Security:** Validating compatibility on Samsung One UI 8.5/9 with a focus on restricted settings and background services.
* **Autonomous Agent Sandboxing:** Architecting deterministic boundaries for local LLMs and tools via MCP.

---

<details>
<summary><b>🛠️ Full Technical Arsenal (Click to expand)</b></summary>
<br>

| Layer | Tools & Technologies |
|---|---|
| **Core Languages** | `Rust` · `Kotlin` · `Python` · `TypeScript` · `Bash` · `C# (.NET)` |
| **Mobile & Client** | Android 16/17 (One UI 8.5/9) · Jetpack Compose · Compose Multiplatform · Electron · React |
| **Backend & Services** | Next.js 16 · FastAPI · Node.js · Supabase (Postgres 17 / RLS) |
| **Security & Crypto** | Hardware Android Keystore · SQLCipher (AES-256) · Windows DPAPI · RAM Inspection |
| **Signals & OSINT** | RTL-SDR (Live RF) · OpenCelliD · CellMapper · Scapy (PCAP) · NetworkX · Cytoscape.js |
| **AI Tooling & Packaging** | Model Context Protocol (MCP) · `uv` toolchain · PyTorch · Local LLMs (Ollama) |

</details>

<details>
<summary><b>🏛️ Engineering Philosophy (Click to expand)</b></summary>
<br>

- **Data Sovereignty:** Local-first by default. Sensitive data stays on the operator's machine. Zero telemetry, zero involuntary cloud exposure.
- **Deterministic Rigor:** Exact calculations, reproducible artifacts, and verifiable audit trails over opaque heuristics.
- **Pragmatic Architecture:** System boundaries chosen strictly on threat model and performance requirements, not industry fashion.
- **Human-in-the-Loop:** Automated processes draft and stage; high-consequence operations require explicit human confirmation.

</details>

---

<div align="center">
<sub><b>the silent wish forever remembered</b> · <i>Old life deleted. New framework loading.</i></sub>
</div>