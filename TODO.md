# TODO

## Repository audit — 2026-11-11

Scope: tracked-file inventory, setup/test commands, existing backlog and targeted source review. This is a first-pass audit, not an exhaustive correctness or security certification. Rendered appearance and runtime performance remain unmeasured unless stated below. P1 = correctness/reproducibility first; P2 = follow-up improvement. Effort: S = small, M = moderate, L = substantial.

### Prioritized follow-up

- [ ] **P2: Check profile presentation with external images unavailable** (effort S; risk low).
  - Evidence: README.md embeds external shields and a local assets/profile-banner.svg.
  - Action/benefit: Ensure the introductory text and project links carry the profile when badge requests fail; review the banner at narrow widths.
  - Verify: Preview README at mobile width and with external image loading blocked.

### History review

Baseline: `bdc281704e38` on `dev`; 13 reachable commits, 0 above approximately 400 reviewed-text changed lines (rename detection; common data/generated artifacts excluded). Local remote-tracking refs contain all current commits; remote state was not refreshed. Preserve published history and make future commits one coherent change, usually 50–200 handwritten lines where practical. Include purpose and validation; larger cohesive changes are acceptable. Any later rewrite needs a verified backup, separate clone, per-commit checks and final-tree equivalence.
