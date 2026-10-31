---
name: socrateai-elenchus-lean4-audit
description: Socratic 3-Layer Elenchus verification harness combining SocrateAI-Lean-Lib (comment-stripped zero-sorry Lean 4 audit), rusty-SUNDIALS CVODE stiff ODE conservation, and Rule R-64 provenance receipts.
---

# SocrateAI Elenchus & Lean 4 Formal Audit Skill (`socrateai-elenchus-lean4-audit`)

Use this skill to verify mathematical theorems, Lean 4 formalizations, and numerical ODE/PDE simulations:
1. **Comment-Stripped Lean 4 Audit (`SocrateAI-Lean-Lib`):** Strip `-- ...` and `/- ... -/` comments before scanning for `sorry`, `admit`, or `native_decide`, and classify statements into `PROVEN_INVARIANT`, `QUARANTINED_AXIOM`, or `UNVERIFIED_SORRY`.
2. **Tier-X Numerical Conservation (`rusty-SUNDIALS`):** Verify stiff ODE trajectories (e.g., Robertson kinetics mass conservation $|\Delta m| < 10^{-12}$) and reject any tool reply marked `stub: true` or `ran: false`.
3. **Rule R-64 Provenance:** Bind producer version, tool name, exact received arguments, and git revision into a SHA-256 receipt.
