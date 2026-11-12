<div align="center">

# Xeyronox
**Systems Engineer · Defensive Security · Local-First Architecture**

[![Activity Status](https://img.shields.io/badge/Activity-Low%20Online%20%2F%20Async%20Mode-6b7280?style=flat-square)](#)
[![GitHub](https://img.shields.io/badge/GitHub-getxeyronoxz-1f2937?style=flat-square&logo=github&logoColor=white)](https://github.com/getxeyronoxz)
[![X](https://img.shields.io/badge/X-@xeyronox-1f2937?style=flat-square&logo=x&logoColor=white)](https://x.com/xeyronox)
[![Instagram](https://img.shields.io/badge/Instagram-@xeyronox-1f2937?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/xeyronox)

<br/>

<a href="https://github.com/getxeyronoxz">
  <img src="https://streak-stats.demolab.com/?user=getxeyronoxz&theme=dark&hide_border=true&background=0d1117&ring=38bdf8&fire=38bdf8&currStreakLabel=38bdf8" alt="GitHub Activity & Contribution Stats" />
</a>

> *Old life deleted. New framework loading.*

---

</div>

### 👤 About

I build local-first software, defensive security tools, and high-assurance desktop and mobile systems. My work prioritizes **data sovereignty**, deterministic logic, and software that runs strictly on the operator's machine.

> **Operational Notice:** Operating in **low-activity / async mode** due to personal commitments and offline priorities. I am less online and do not maintain constant presence, advancing code in focused intermittent windows.

* **Current Active Focus:** Directing available development time toward **local-upi-ledger** and low-overhead systems tooling.
* **Systems & Desktop:** Native Windows and Linux utilities, offline data engines, and deterministic tools.
* **Android Security:** In-memory accessibility parsing, 16 KB page alignment for Android 16/17, and hardware Keystore cryptographic isolation.

---

### 🛠️ Skills

| Domain | Technologies & Frameworks |
|:---|:---|
| **Languages** | `Rust` · `Kotlin` · `Python` · `TypeScript` · `C# (.NET)` · `Bash` |
| **Desktop & Systems** | Win32 API · .NET Native AOT · Electron · CLI Tooling |
| **Mobile & Android** | Android 16/17 (Samsung One UI 8.5/9) · Jetpack Compose · Room · SQLCipher |
| **Security & Privacy** | Hardware Android Keystore · SQLCipher (AES-256) · Windows DPAPI · RAM Inspection |
| **Signals & OSINT** | RTL-SDR (Live RF) · OpenCelliD · CellMapper · Scapy (PCAP) · NetworkX · Cytoscape.js |

---

### ⚡ Selected Projects

#### 🛡️ [`local-upi-ledger`](https://github.com/getxeyronoxz/local-upi-ledger) &nbsp; `🟡 [In Deployment / Current Focus]`
*Zero-permission UPI transaction aggregator engineered for Android 16 & 17.*
* **Air-Gapped Operation:** Operates with `0 INTERNET` permissions in manifest; storage encrypted with SQLCipher 4.x (AES-256 GCM) backed by hardware Android Keystore.
* **In-Memory Extraction:** Inspects active `AccessibilityNodeInfo` hierarchy to parse transaction logs past banking `FLAG_SECURE` screen restrictions without root.
* **Stack:** `Kotlin` · `Jetpack Compose` · `SQLCipher` · `Room` · `AGPL-3.0`

#### ⚖️ [`open-merchant`](https://github.com/getxeyronoxz/open-merchant) &nbsp; `🟢 [v1.0.1 / Frozen Baseline]`
*AI-native desktop workbench for commercial decision modeling & exact-decimal economics.*
* **Status:** Completed baseline release (`v1.0.1`). Currently frozen with no ongoing updates or active feature additions.
* **Core Function:** Exact-decimal ledger calculations (zero floating-point drift) with atomic disk persistence and an air-gapped read-only stdio MCP server.
* **Stack:** `TypeScript` · `Electron` · `React` · `Zod` · `stdio MCP` · `AGPL-3.0`

#### 📡 [`XGhostSignal`](https://github.com/getxeyronoxz/XGhostSignal) &nbsp; `🟢 [v0.2.0 / Stable Baseline]`
*Local-first OSINT & cellular intelligence workbench.*
* **Status:** Stable release (`v0.2.0`). Dual high-speed CLI (`xgs`) and web console.
* **Core Function:** Live RTL-SDR RF spectrum burst capture, cell-tower geospatial correlation, ADS-B flight tracking, and NetworkX entity correlation.
* **Stack:** `Python 3.9+` · `FastAPI` · `Typer` · `SQLAlchemy` · `PyRtlSdr` · `Scapy` · `MIT`

---

### 🏛️ Philosophy

1. **Data Sovereignty:** Local-first by default. Sensitive operational data stays exclusively on the operator's machine. Zero telemetry, zero involuntary cloud exposure.
2. **Deterministic Rigor:** Exact calculations, reproducible artifacts, and verifiable audit trails over opaque heuristics or floating-point approximations.
3. **Pragmatic Architecture:** System boundaries (local, hybrid, or cloud-assisted) are chosen strictly on threat model and performance requirements, not industry fashion.
4. **Human-in-the-Loop:** Autonomous processes only draft and stage; high-consequence operations require explicit human confirmation.

---

<div align="center">
<sub><b>the silent wish forever remembered</b> · <i>Old life deleted. New framework loading.</i></sub>
</div>