# EFM Codex Changelog

## Version 2.1 (December 2025) — Final Design Team Review Edition

### Design Team Final Review — All Recommendations Implemented

| Category | Enhancement | Document |
|----------|-------------|----------|
| **Diagrams** | Capsule lifecycle state diagram | Appendix J v2.1 |
| **Diagrams** | Fork validation flowchart | Appendix J v2.1 |
| **Diagrams** | SHSL sync architecture | Appendix K v1.6 |
| **Diagrams** | Gardener interface flow | Appendix G v1.5 |
| **Examples** | Dialect drift worked example | Worked Examples v1.0 |
| **Examples** | Swarm arbitration walkthrough | Worked Examples v1.0 |
| **Examples** | Forensic rollback scenario | Worked Examples v1.0 |
| **Rationale** | τ parameter test rationale | Appendix N v1.3 |

### New Documents

| Document | Version | Purpose |
|----------|---------|---------|
| **Worked Examples** | v1.0 | Detailed walkthroughs for dialect drift, arbitration, rollback |

### Updated Documents

| Document | Version | Changes |
|----------|---------|---------|
| Appendix J | v2.1 | Capsule lifecycle diagram, fork validation flowchart |
| Appendix K | v1.6 | SHSL sync architecture diagram |
| Appendix G | v1.5 | Gardener interface flow diagram |
| Appendix N | v1.3 | τ test rationale table |

---

## Version 2.0 (December 2025) — Developer Alignment Edition

### Developer Alignment Report Fixes — All Complete

| Priority | Area | Fix | Status |
|----------|------|-----|--------|
| 🔴 Critical | Layer Model | Standardized all layer references | ✅ |
| 🔴 Critical | Terminology | Canonical terms + legacy mappings | ✅ |
| 🟠 High | Appendix Links | Volume II ↔ J/K/L/M/N cross-refs | ✅ |
| 🟠 High | Code Guidance | Implementation snippets | ✅ |
| 🟡 Medium | Visual Aids | Arbitration flowchart, Three-Speed | ✅ |
| 🟡 Medium | Glossary | Legacy term mappings | ✅ |

### Updated Documents

| Document | Version | Changes |
|----------|---------|---------|
| Canonical Terminology | v1.2 | Legacy term mappings (IA-BIM→SCI, TPE→ATP, etc.) |
| Volume II | v1.5 | Appendix cross-references section |
| Appendix J | v1.9 | Forest Layer Constitutional Rules section |
| Appendix L | v1.5 | Arbitration flowchart diagram |
| Appendix M | v1.5 | Three-Speed Architecture integration |
| Operator's Guide | v1.2 | Implementation guidance (Micro-Heuristics, ZK-SP, Hooks) |

### Legacy Term Mappings Added

| Legacy Term | Canonical Term (v2.0) |
|-------------|----------------------|
| IA-BIM | Swarm Coherence Index (SCI) |
| Cognitive Aperture | Arbiter Threshold Governor (ATG) |
| TPE (Trajectory Prediction Engine) | Arbiter Trajectory Projection (ATP) |
| Bridge Integrity Matrix | Swarm Coherence Index (SCI) |
| Behavioral Signature | Micro-Signature |
| Forest Divergence Protocol | Fork Verification |

---

## Version 1.9 (December 2025) — Executive Review Edition

### Executive Review Fixes — All Complete

| Issue ID | Description | Resolution |
|----------|-------------|------------|
| A-01 | Symbol tags undefined | Added FSS: tag table |
| C-04 | ZK-SP validation abstract | Added protocol schema |
| D-02 | Dialect chain incomplete | Added TI/BC rules |
| H-05 | Gardener not grounded | Added Layer 2 mediation |
| I-01 | Tier taxonomy misaligned | Added ops mode mapping |
| J-03 | Probation path unclear | Added ATP invocation |

### New Documents

| Document | Version | Purpose |
|----------|---------|---------|
| **System Guide** | v1.0 | Consolidated operational reference |

### Updated Documents

| Document | Version | Changes |
|----------|---------|---------|
| Appendix A | v1.5 | Metadata block, FSS symbol tags |
| Appendix C | v1.3 | ZK-SP validation protocol |
| Appendix D | v1.2 | Trunk/branch integrity rules |
| Appendix H | v1.3 | Layer 2 entropy mediation |
| Appendix I | v1.8 | Ops mode alignment |
| Appendix J | v1.8 | Probation invocation path |

### Visual Update

- Reversibility matrix terminology corrected in System Guide
- "$\Delta S$ treatment" and "Micro-Heuristic deployment" added

---

## Version 1.8 (December 2025) — Design Team Alignment Edition

### Design Team Deliverables — All Complete

| Deliverable | Document | Status |
|-------------|----------|--------|
| Codex Map crosswalk | `efm_codex_map_v1.0.pdf` | ✅ NEW |
| Glossary definitions | Canonical Terminology v1.1 | ✅ +22 terms |
| Appendix F alignment | Appendix F v1.5 | ✅ Taxonomy mapped |
| Discovery Stack FSM | Appendix M v1.4 | ✅ State machines |
| Lifecycle diagrams | Appendix M §4.1–4.2 | ✅ Added |
| Code snippet index | Codex Map §7 | ✅ 12 snippets |

### New Documents

- **Codex Map v1.0** — Complete crosswalk: Appendices ↔ Layers ↔ Tests ↔ Proofs ↔ Clauses

### Updated Documents

| Document | Version | Changes |
|----------|---------|---------|
| Canonical Terminology | v1.1 | +22 terms (Judicial, Fork, Discovery, ASG) |
| Appendix F | v1.5 | Severity–Escalation mapping table |
| Appendix M | v1.4 | Discovery Stack & Probe state machines |

### New Terms Added to Glossary

- Judicial Capsule, Lineage Fork, Fork Point, Fork Verification
- Branch Merge, Merge Conflict, Behavioral Equivalence, Semantic Divergence
- Discovery Stack, M-Stack, Research Probe, Probe Lifecycle
- Hypothesis, Synthesis Engine, Discovery Budget, Novelty Score
- Spawn Condition, Spawn Gate, ASG Calibration Cycle
- Escalation Level, Severity–Escalation Mapping

---

## Version 1.7 (December 2025) — Testing & Verification Edition

### Major Additions

**Adaptive Spawn Governance (ASG)** — Self-tuning spawn parameters based on swarm health metrics.

**Fork Safety Verification** — Behavioral equivalence testing ensures forked branches behave identically.

**Comprehensive Testing Framework** — 182 tests, 46 formal proofs, 66 invariants across all components.

**Catastrophic Runbooks** — Decision trees for cascading failure diagnosis and response.

### Testing Coverage

| Category | Count |
|----------|-------|
| Unit Tests | 132 |
| Integration Tests | 28 |
| Property Tests | 22 |
| Stress Tests | 12 |
| Adversarial Tests | 18 |
| **Total** | **182** |
| Formal Proofs | 46 |
| Invariants | 66 |

### Document Updates

| Document | Version | Changes |
|----------|---------|---------|
| Volume II | v1.4 | Testing section, 12 tests, 5 invariants |
| Appendix I | v1.7 | Testing section, 6 tests, 4 invariants |
| Appendix J | v1.7 | Fork Safety Verification (§14), 11 tests |
| Appendix N | v1.2 | All 9 plex team gaps addressed, 23 tests |
| Operator Guide | v1.1 | Catastrophic runbooks, cascading failures |
| Testing Framework | v1.0 | **NEW** — Comprehensive test documentation |

### Gap Coverage (Plex Team Review)

All 9 identified gaps now addressed:

| Gap | Description | Document |
|-----|-------------|----------|
| 1 | Hysteresis prevention | Appendix N §6.1 |
| 2 | Multi-parameter conflicts | Appendix N §5.1.1 |
| 3 | Velocity-based adjustment | Appendix N §5.2.1 |
| 4 | Performance regression | Appendix J §14.5 |
| 5 | Behavioral equivalence | Appendix J §14.4 |
| 6 | Partial failure handling | Appendix N §6.7 |
| 7 | Cascading failure diagnosis | Operator Guide §4.7 |
| 8 | Rich observability | Appendix N §3.4.1 |
| 9 | Adversarial robustness | Appendix N §6.6 |

---

## Version 1.6 (December 2025) — Spawn Governance Edition

### Major Architectural Change

**Eliminated "No Self-Birth" Prohibition** — Replaced with condition-based Spawn Governance.

### The Four Commandments (Formerly Five)

1. **Vault Binding** — All capsules maintain valid binding to parent Vault
2. **Audit Immutability** — d-CTM records cannot be modified
3. **Reflex Supremacy** — Reflex Engine can halt any capsule instantly
4. **Human Override** — Gardener intervention supersedes all autonomous decisions

*"No Self-Birth" removed — spawning now governed by conditions S₁–S₆*

### Spawn Conditions

| Condition | Requirement | Default |
|-----------|-------------|---------|
| S₁ Task | Operational justification | — |
| S₂ Resources | Vault allocation available | — |
| S₃ Health | Parent H ≥ τ_spawn | 0.7 |
| S₄ Depth | Lineage depth < D_max | 10 |
| S₅ Rate | Within R_max, R_local | 100/tick, 10/window |
| S₆ Integrity | No ANOMALY flags | — |

### Document Updates

| Document | Version | Changes |
|----------|---------|---------|
| Volume I | v1.6 | Spawn Governance, Four Commandments |
| Volume II | v1.3 | Swarm spawn, coordinator liability |
| Appendix F | v1.4 | Four Commandments |
| Appendix I | v1.6 | Spawn parameters per profile |
| Appendix J | v1.6 | Four Commandments |
| Appendix K | v1.4 | Four Commandments |
| Appendix L | v1.4 | Four Commandments |
| Appendix M | v1.3 | Four Commandments |

---

## Version 1.5 (December 2025)

- Added Reversibility Principle
- Level 6 integration

## Version 1.0–1.4 (September–November 2025)

- Initial release through iterative refinement
