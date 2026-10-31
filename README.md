# 🤝 HiveMind × AMCP × SocrateAI — Unified Collaboration Hub

[![License: AGPL-3.0 / MIT](https://img.shields.io/badge/License-AGPL--3.0%20%2F%20MIT-blue.svg)](https://github.com/xaviercallens/HiveMind)
[![OpenRouter Live](https://img.shields.io/badge/HiveMind_OpenRouter-15+_Bees_Live-brightgreen)](https://hivemind-openrouter-1003063861791.us-central1.run.app/signup)
[![La Ruche Portal](https://img.shields.io/badge/La_Ruche-P2P_GPU_Swarm-amber)](https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app/)
[![Zenodo GWAYA](https://zenodo.org/badge/DOI/10.5281/zenodo.23123923.svg)](https://doi.org/10.5281/zenodo.23123923)
[![Zenodo OptimalEnergyAI](https://zenodo.org/badge/DOI/10.5281/zenodo.23295142.svg)](https://doi.org/10.5281/zenodo.23295142)

> **Official Cross-Project Integration & Open Collaboration Repository by [Xavier Callens](https://github.com/xaviercallens).**
> Uniting **AMCP** (Agent Mesh Communication Protocol), **Project HiveMind (`La Ruche`)**, **AutoevolveAI (`ANSE`)**, **GWAYA (`Gwen-Laya`)**, **OptimalEnergyAI** ($A_2$ & $E_8$ Lattice Geometry), **SocrateAI-Scientific-Elenchus**, **SocrateAI-Lean-Lib**, **rusty-SUNDIALS**, and our open-source **Community Fork Bridges (`XSwaT`, `xLayerStoRm`, `xensorSharp`, `xlaya`, `XHillock`)**.

---

## 🧭 Architecture Unifiée (4 Couches) / Unified 4-Layer Stack

```
+--------------------------------------------------------------------------------------------------+
| LAYER 1 — ORCHESTRATION MULTI-AGENTS & TRANSPORT LATENT (AMCP + OptimalEnergyAI + XSwaT)         |
| • AMCP Event-Driven Mesh Protocol + XSwaT Prefill-Free Latent KV-Cache Transfer                  |
| • OptimalEnergyAI A2 Hexagonal RoPE Plane Quantizer (3.775% Fejes Toth gain) + E8 (2.5 bits/dim) |
| • xlaya 1-Pass System-1 Router + XHillock 0-VRAM Offline HDC/VSA Agent Memory                    |
+--------------------------------------------------------------------------------------------------+
                                                │
                                                ▼
+--------------------------------------------------------------------------------------------------+
| LAYER 2 — CALCUL DÉCENTRALISÉ < 1,5 Go VRAM (HiveMind + RunuX TurboQuant + xLayerStoRm)          |
| • HiveMind OpenRouter (15+ Specialist MoE Bees, Kelly HMT Reciprocity Ledger, <1.5s Steam Pause) |
| • xLayerStoRm Double-Buffered PCIe MoE Expert Streaming (32 experts in 1,270 MiB active VRAM)    |
| • xensorSharp 1-Click Native Worker (Windows/macOS/Linux/iOS, zero WSL2) + RunuX TurboQuant 4.8x |
+--------------------------------------------------------------------------------------------------+
                                                │
                                                ▼
+--------------------------------------------------------------------------------------------------+
| LAYER 3 — PORTE FAIL-CLOSED ANTI-STUB & AUTO-RÉPARATION (GWAYA + AutoevolveAI / ANSE)            |
| • GWAYA Zero-Stub AST Gate (rejects pass, ..., mock_*, todo!(), sorry with E = 10^6 penalty)     |
| • Calibrated Laya Selective Abstention + Arm A3 Sample-and-Repair Loop (Best-of-3 + 3 Repairs)   |
+--------------------------------------------------------------------------------------------------+
                                                │
                                                ▼
+--------------------------------------------------------------------------------------------------+
| LAYER 4 — CERTIFICATION SCIENTIFIQUE & PREUVE FORMELLE TIER-X (Elenchus + Lean 4 + SUNDIALS)     |
| • SocrateAI-Scientific-Elenchus & elenchus-solvers-mcp (Rule R-64 Provenance + Stub Refusal)     |
| • SocrateAI-Lean-Lib (14 domains, 40+ modules, 0 sorry, comment-stripped kernel verification)    |
| • rusty-SUNDIALS Pure-Rust CVODE Stiff ODE Solver + OpenAI-NSE-Epistemic-Audit (Knudsen Check)   |
+--------------------------------------------------------------------------------------------------+
```

---

## ⚡ Start Here in 60 Seconds — Choose Your Role (`Developers` • `Contributors` • `HiveMiners` • `HiveMaster`)

| Role | Who You Are | Your 60-Second Onboarding Path | Primary Entry Point |
| :--- | :--- | :--- | :--- |
| **💻 1. Developers** | AI app builders, IDE users (`Claude Code`, `Cursor`, `Continue`, `Google Antigravity SDK`) | Sign up or log in for a free `+100 HMT` key and call `15+` specialized MoE Bees (`hivemind/coder`, `hivemind/bee-stars`, `hivemind/bee-lean-prover`, `hivemind/bee-rusty-sundials`) | 👉 **[Sign Up & Login (`/signup`)](https://hivemind-openrouter-1003063861791.us-central1.run.app/signup)** |
| **🛠️ 2. Contributors** | Python/Rust/CUDA engineers, ML researchers, Lean 4 formal provers | Pick one of the 4 Working Groups in [`COLLABORATION.md`](COLLABORATION.md), co-develop with `hivemind/coder`, and pass the `GWAYA` Zero-Stub & 5-Layer Security gates | 👉 **[`COLLABORATION.md`](COLLABORATION.md)** & **[`xaviercallens/HiveMind`](https://github.com/xaviercallens/HiveMind)** |
| **⛏️ 3. HiveMiners** | Gamers & GPU owners (`8–24 GB VRAM`: RTX 2060–4090, T4, ROCm/DirectML, Apple M1–M4) | Provide idle GPU cycles under `<= 1.5 GB` citizen Split-ML VRAM (`<= 6.5 GB` full ceiling) with `< 150 ms` automatic game preemption and earn `~112–115 HMT/hr` | 👉 **[Join as a HiveMiner (`/rejoindre`)](https://hivemind-openrouter-cfhmhmvv5a-uc.a.run.app/rejoindre?lang=fr)** & **[La Ruche Portal](https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app/)** |
| **👑 4. HiveMaster** | Swarm administrator (`role="admin"`), cluster coordinator & security operator | Operate the OpenRouter & BOINC coordinators, enforce the Thermodynamic Monotonic Ratchet ($\Delta \mathcal{L}_{\text{eval}} \le 0$), Multi-Krum, Canary anti-farming & 24/7 Cyber Defense | 👉 **[HiveMaster Command Runbook (Below)](#-4-hivemaster-swarm-admin--governance-ratchet--247-security-ops)** |

---

### 💻 1. Developers — Get Your Free `hm-...` Key & Call 15+ Specialized Bees
- **Sign Up & Returning User Login (`+100.0 HMT` free starter grant):** [https://hivemind-openrouter-1003063861791.us-central1.run.app/signup](https://hivemind-openrouter-1003063861791.us-central1.run.app/signup)
- **La Ruche Community Portal:** [https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app/](https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app/)

```python
# Use with Google Antigravity SDK, Claude Code, Cursor, or OpenAI Python SDK
import asyncio
from google.antigravity import Agent, LocalOpenAIAgentConfig

async def main():
    config = LocalOpenAIAgentConfig(
        model="hivemind/bee-stars",  # or "hivemind/coder", "hivemind/bee-lean-prover", "hivemind/bee-rusty-sundials"
        base_url="https://hivemind-openrouter-1003063861791.us-central1.run.app/v1",
    ).lightweight()
    async with Agent(config=config) as agent:
        reply = await agent.chat("Optimize our Symplectic Velocity-Verlet N-Body orbital step for KEPLER-HM-442b.")
        print(await reply.text())

asyncio.run(main())
```

### 🛠️ 2. Contributors — Run the 4-Layer Cross-Project Verification Suite & Open a PR
```bash
git clone https://github.com/xaviercallens/HiveMind-AMCP-Collaboration.git
cd HiveMind-AMCP-Collaboration
PYTHONPATH=src pytest tests/ -v
```
- **Zero-Stub & Anti-Boubou Policy:** Every contribution is verified against `GWAYA` AST anti-stub gates ($E = 10^6$ fail-closed penalty on `pass` / `...` / `TODO` / `sorry`) and deterministic unit tests.

### ⛏️ 3. HiveMiners — Provide Your Idle GPU (`8–24 GB VRAM`) with `< 150 ms` Game Preemption
```bash
# Option A — Live OpenRouter Inference Producer (serve local Ollama / llama.cpp models & earn HMT per 1k tokens):
curl -sSLO https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app/scripts/hivemind_producer_agent.py
python3 hivemind_producer_agent.py \
  --gateway https://hivemind-openrouter-1003063861791.us-central1.run.app \
  --handle your-miner-tag

# Option B — Nocturnal BOINC / DiLoCo QLoRA Worker (train 6-domain & 24-Bee experts during idle/night windows):
curl -sSLO https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app/scripts/hivemind_boinc_idle_worker.py
python3 hivemind_boinc_idle_worker.py \
  --coordinator https://hivemind-at-home-ruche-cfhmhmvv5a-uc.a.run.app \
  --handle your-miner-tag --domain physics_sim --once
```

### 👑 4. HiveMaster (Swarm Admin) — Governance, Ratchet & 24/7 Security Ops
- **Coordinator & Gateway Control:** Operates `hivemind-openrouter` and `hivemind-at-home-ruche`, warm-model residency routing (`HM-S16-06`), and remote producer VRAM caps/pauses (`HM-S16-05`).
- **Thermodynamic Monotonic Ratchet ($\Delta \mathcal{L}_{\text{eval}} \le 0$) & GWAYA Gate:** Promotes new MoE adapters only when held-out loss improves across all domains and paired McNemar $p < 0.05$.
- **Byzantine, Canary & Cyber Defense:** Runs $2\sigma$-clipped Multi-Krum, 10% architecture-matched CUDA replay (`HM-S10-08`), Canary logit anti-farming (`HM-S33-02`), 5-Layer `PRSecurityScanner`, and 24/7 automated monitoring (`hivemind_30min_monitor.py` & `hivemind_2h_cyber_protection.py`).

---

## 📦 Catalogue des Projets Unifiés (`11` Projets Originaux + `8` Ponts Forks `x*`)

### A. Projets Originaux (`original_core_ip`)
| Projet | Dépôt GitHub | Rôle dans la Pile Commune |
| :--- | :--- | :--- |
| **1. Project HiveMind** | [`xaviercallens/HiveMind`](https://github.com/xaviercallens/HiveMind) | Essaim GPU P2P citoyen (`<1,5 Go` VRAM), OpenRouter `15+` Abeilles & marché Kelly `HMT` |
| **2. AMCP** | [`xaviercallens/amcp-v1.5-opensource`](https://github.com/xaviercallens/amcp-v1.5-opensource) | Agent Mesh Communication Protocol — bus événementiel multi-agents distribué & mobile |
| **3. AutoevolveAI (ANSE)** | [`xaviercallens/AutoevolveAI`](https://github.com/xaviercallens/AutoevolveAI) | Modèle neuro-symbolique basé sur l'énergie physique ($E = 10^6$ fail-closed) |
| **4. GWAYA (`Gwen-Laya`)** | [`xaviercallens/GWAYA-GwenLayaOpenModel`](https://github.com/xaviercallens/GWAYA-GwenLayaOpenModel) | Porte AST zéro-stub, score sélectif calibré `Laya` & boucle de réparation `A3` (`DOI 10.5281/zenodo.23123923`) |
| **5. OptimalEnergyAI** | [`xaviercallens/triangular-universal-optimality-lean`](https://github.com/xaviercallens/triangular-universal-optimality-lean) | Optimalité universelle des réseaux $A_2$ (plans RoPE 2D) et Gosset $E_8$ (`2,5 bits/dim`, `DOI 10.5281/zenodo.23295142`) |
| **6. SocrateAI-Lean-Lib** | [`xaviercallens/SocrateAI-Lean-Lib`](https://github.com/xaviercallens/SocrateAI-Lean-Lib) | Bibliothèque formelle Lean 4 (14 domaines scientifiques, 40+ modules, `0 sorry`, sans dépendance Mathlib) |
| **7. rusty-SUNDIALS** | [`xaviercallens/rusty-SUNDIALS`](https://github.com/xaviercallens/rusty-SUNDIALS) | Solveur d'EDO raides CVODE traduit de C (44K LOC) vers Rust sûr et vérifié |
| **8. OpenAI-NSE-Epistemic-Audit** | [`xaviercallens/OpenAI-NSE-Epistemic-Audit`](https://github.com/xaviercallens/OpenAI-NSE-Epistemic-Audit) | Audit physique (nombre de Knudsen & censure thermodynamique) des preuves de blow-up PDE (`DOI 10.5281/zenodo.22696717`) |
| **9. SocrateAI-Scientific-Elenchus** | [`xaviercallens/SocrateAI-Dual-Scale-Agora-Lab`](https://github.com/xaviercallens/SocrateAI-Dual-Scale-Agora-Lab) | Protocole de contre-interrogatoire socratique à 3 couches (Lean 4 + ODE + physique) |
| **10. elenchus-solvers-mcp** | Serveur MCP Tier-X | Serveur JSON-RPC stdio en Rust avec provenance `R-64` et refus strict des stubs |
| **11. RunuX & runux-ai-runtime** | [`xaviercallens/rust-linux-mini-kernel`](https://github.com/xaviercallens/rust-linux-mini-kernel) | Noyau `#![no_std]` Rust vérifié en Lean 4 & compression KV-cache `TurboQuant` (`4,8x`) |

### B. Ponts d'Adaptation Open-Source (`community_fork_bridge` — préfixe `x*`)
| Pont Fork `x*` | Dépôt GitHub | Intégration dans la Pile Commune |
| :--- | :--- | :--- |
| **`XSwaT`** | [`xaviercallens/XSwaT`](https://github.com/xaviercallens/XSwaT) | Transfert d'états latents KV-cache sans texte entre Abeilles sur le bus `AMCP` (`HM-S35-01`) |
| **`xLayerStoRm`** | [`xaviercallens/xLayerStoRm`](https://github.com/xaviercallens/xLayerStoRm) | Streaming d'experts MoE en double-buffer sur PCIe sous `<= 1 536 MiB` de VRAM (`HM-S35-04`) |
| **`xensorSharp`** | [`xaviercallens/xensorSharp`](https://github.com/xaviercallens/xensorSharp) | Exécutable citoyen natif `.NET` / Windows / macOS / iOS sans WSL2 ni Python (`HM-S35-04`) |
| **`xlaya`** | [`xaviercallens/xlaya`](https://github.com/xaviercallens/xlaya) | Routeur de décision *System 1* non-autorégressif en une passe (`100+` langues) |
| **`XHillock`** | [`xaviercallens/XHillock`](https://github.com/xaviercallens/XHillock) | Mémoire locale hors-ligne sans GPU (`0 Go VRAM`) par calcul hyperdimensionnel (HDC/VSA) |
| **`xdatabricks-agent-skills`** | [`xaviercallens/xdatabricks-agent-skills`](https://github.com/xaviercallens/xdatabricks-agent-skills) | Skills B2B Databricks Spark/Delta pour Claude Code, Cursor & Copilot |
| **`xskills-for-copilot-studio`** | [`xaviercallens/xskills-for-copilot-studio`](https://github.com/xaviercallens/xskills-for-copilot-studio) | Validation YAML et schémas Microsoft Copilot Studio pour agents de code |
| **`xProCompta`** | [`xaviercallens/xProCompta`](https://github.com/xaviercallens/xProCompta) | Gestion comptable souveraine TPE/PME couplée à un nœud local `HiveMind` + `XHillock` |

---

## 🛠️ Skills Standards (`SKILL.md`) Inclus pour Claude Code, Cursor, Copilot, Agensi.io & Antigravity

- [`skills/amcp-hivemind-swarm/SKILL.md`](skills/amcp-hivemind-swarm/SKILL.md) — Orchestration multi-agents `AMCP` + `HiveMind OpenRouter` (`15+` Abeilles, `<1,5 Go` VRAM).
- [`skills/gwaya-zero-stub-mcp-gate/SKILL.md`](skills/gwaya-zero-stub-mcp-gate/SKILL.md) — Porte fail-closed anti-stub `GWAYA` + mémoire locale `XHillock` + routeur `xlaya`.
- [`skills/socrateai-elenchus-lean4-audit/SKILL.md`](skills/socrateai-elenchus-lean4-audit/SKILL.md) — Audit formel Lean 4 (`SocrateAI-Lean-Lib`) & solveur `rusty-SUNDIALS` avec provenance `R-64`.

Consultez [**`COLLABORATION.md`**](COLLABORATION.md) pour rejoindre l'un des 4 groupes de travail ouverts.
