# EU AI Act Evidence Survivability Benchmark

This repository contains a **free, artifact-only benchmark**
to stress-test AI audit evidence assembly under deadline pressure.

It is **not** a compliance solution.
It is a way to see where evidence breaks under stress.

---

## What this is

- A reproducible **72h hostile audit stress test**
- Focused on **evidence survivability**, not legal correctness
- Artifact-only: schemas, prompts, examples
- Designed to expose failure modes under pressure

---

## What this is not

- Not legal advice
- Not a compliance guarantee
- Not a regulator-approved framework
- Not an operational control system

---

## Why this exists

Most audit failures do not happen because teams lack documentation.
They happen because documentation **contradicts itself under deadline pressure**.

This benchmark focuses on:
- missing links
- version drift
- narrative inconsistencies
- unverifiable edits

The goal is not perfection.
The goal is **survivability**.

---

## Repository structure

- `/baseline`  
  Reference to the free EU AI Act Layer Lite baseline.

- `/benchmark`  
  Reproducible A/B stress test:
  - manual / ad-hoc evidence assembly
  - vs structured baseline + controlled vocabulary

- `/docs`  
  Explicit scope, limitations, and known failure modes.

---

## How to use (minimal)

1. Define or generate a realistic **high-risk AI scenario**
2. Use the benchmark prompt in `/benchmark`
3. Paste the baseline JSON
4. Run the A/B simulation
5. Compare **failure modes**, not scores

---

## Outputs

- `scenario_a.log`
- `scenario_b.log`
- `scorecard.json`
- `evidence_bundle.html`
- `export_instructions.txt`

All outputs are static and reviewable.

---

## Limitations

- No cryptographic integrity guarantees
- No claim of completeness
- No protection against bad-faith inputs
- Human judgment is intentionally preserved

---

## Final note

This repository is intentionally boring.

Boring survives audits.
