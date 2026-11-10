<div align="center">

# Xeyronox
**Systems Engineering · Defensive Security · High-Assurance Local Tooling**

> *Old life deleted. New framework loading.*  
> <sub>the silent wish forever remembered</sub>

---

</div>

### ⚡ Systems & Workbenches

#### 🛡️ [`local-upi-ledger`](https://github.com/getxeyronoxz/local-upi-ledger) &nbsp; `[In Active Deployment]`
*Local-first UPI transaction aggregator for Samsung Galaxy / Android 16 & 17.*
- **Current State:** Active hardware validation & deployment (tested on One UI 8.5/9, Samsung Galaxy F15 5G).
- **Security Boundaries:** Zero internet permissions (`0 INTERNET` in manifest); SQLCipher 4.x encrypted persistence bound to hardware Android Keystore (AES-256 GCM).
- **Runtime Mechanism:** In-memory `AccessibilityNodeInfo` hierarchy inspection to extract transaction receipts past banking `FLAG_SECURE` restrictions without root.
- **Stack:** `Kotlin` · `Jetpack Compose` · `SQLCipher` · `Room` · `AGPL-3.0`

#### ⚖️ [`open-merchant`](https://github.com/getxeyronoxz/open-merchant) &nbsp; `[Completed / Stable v1.0.1]`
*AI-native, local-first desktop workbench for commercial decision modeling & unit economics.*
- **Current State:** Stable production release (`v1.0.1`). Cross-platform desktop binaries for Windows, macOS, and Linux.
- **Core Engine:** Exact-decimal ledger calculations (zero floating-point distortion, zero LLM math); atomic on-disk project stores with verifiable provenance.
- **Human Gate:** "Draft Desk" staging queue where model outputs remain inert until human acceptance; includes read-only stdio MCP server (`open-merchant-mcp`).
- **Stack:** `TypeScript` · `Electron` · `React` · `Zod` · `stdio MCP` · `AGPL-3.0`

#### 📡 [`XGhostSignal`](https://github.com/getxeyronoxz/XGhostSignal) &nbsp; `[Completed / Stable v0.2.0]`
*Local-first OSINT & cellular intelligence workbench.*
- **Current State:** Stable release (`v0.2.0`). Dual fast CLI (`xgs`) and browser-based analyst console.
- **Capabilities:** Cell tower mapping (OpenCelliD/CellMapper), live RTL-SDR RF spectrum burst detection, ADS-B aircraft tracking, and Cytoscape/NetworkX entity correlation.
- **Stack:** `Python 3.9+` · `FastAPI` · `Typer` · `SQLAlchemy` · `PyRtlSdr` · `Scapy` · `MIT`

---

<details>
<summary><b>🛠️ Technical Toolkit (Click to expand)</b></summary>
<br>

| Layer | Tools & Technologies |
|---|---|
| **Core Languages** | `Rust` · `Kotlin` · `Python` · `TypeScript` · `Bash` · `C# (.NET)` |
| **Mobile & Client** | Android 16/17 (One UI 8.5/9) · Jetpack Compose · Compose Multiplatform · Electron · React |
| **Services & Web** | Next.js 16 (App Router) · FastAPI · Node.js · Supabase (Postgres 17 / RLS) |
| **Security & Crypto** | Hardware Android Keystore · SQLCipher (AES-256) · Windows DPAPI · RAM Inspection |
| **Signals & OSINT** | RTL-SDR (Live RF) · OpenCelliD · CellMapper · Scapy (PCAP) · NetworkX · Cytoscape.js |
| **AI Tooling & Packaging** | Model Context Protocol (MCP) · `uv` toolchain · PyTorch · Local LLMs (Ollama) |

</details>

<details>
<summary><b>🏛️ Operational Doctrine (Click to expand)</b></summary>
<br>

- **Data Sovereignty:** Local-first by default. Sensitive operational data stays exclusively on the operator's machine. Zero telemetry, zero involuntary cloud exposure, zero silent ingestion.
- **Deterministic Rigor:** Exact calculations, reproducible artifacts, and verifiable audit trails over opaque heuristics.
- **Pragmatic Architecture:** System boundaries (local, hybrid, or cloud-assisted) chosen strictly on threat model and performance requirements.
- **Operator-in-the-Loop:** Autonomous processes only draft and stage; high-consequence operations require explicit human confirmation.

</details>

---

### 📡 Connect

[![GitHub](https://img.shields.io/badge/GitHub-getxeyronoxz-1f2937?style=flat-square&logo=github&logoColor=white)](https://github.com/getxeyronoxz)
[![X](https://img.shields.io/badge/X-@xeyronox-1f2937?style=flat-square&logo=x&logoColor=white)](https://x.com/xeyronox)
[![Instagram](https://img.shields.io/badge/Instagram-@xeyronox-1f2937?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/xeyronox)

---

<div align="center">
<sub><b>the silent wish forever remembered</b> · <i>Old life deleted. New framework loading.</i></sub>
</div>