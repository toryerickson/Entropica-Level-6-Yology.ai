# EFM Codex Changelog

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
