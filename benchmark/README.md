# Benchmark: Evidence Survivability Stress Test

This benchmark tests how well an AI audit evidence bundle survives
realistic deadline pressure.

It does **not** test legal correctness.
It tests whether your documentation stays coherent when things get stressful.

---

## What this benchmark does

The benchmark simulates a **72-hour hostile audit scenario** where:

- evidence must be assembled quickly
- documentation is incomplete or fragmented
- assumptions change mid-process
- different stakeholders ask conflicting questions

The goal is to observe **where evidence breaks**, not to prove compliance.

---

## What you need

You only need existing documentation:

- model descriptions
- risk assessments
- process notes
- policies, tickets, wikis, PDFs
- anything you would realistically hand to an auditor

No special tooling is required.

---

## How to run the benchmark

### Step 1: Pick a realistic scenario

Choose a concrete situation, for example:

- “This system is classified as high-risk under the EU AI Act.”
- “An auditor requests evidence within 72 hours.”
- “A regulator challenges one assumption in your risk assessment.”

Write the scenario down in one paragraph.

---

### Step 2: Assemble evidence under time pressure

Using your existing documents:

- map evidence to the baseline structure
- do **not** rewrite everything
- do **not** aim for perfection
- work as you realistically would under pressure

If something is missing, leave it missing.

---

### Step 3: Track failure points

While assembling evidence, note:

- missing links
- version conflicts
- unclear ownership
- contradictory statements
- unverifiable claims
- assumptions that only exist “in people’s heads”

Do not fix them yet.
Just record them.

---

### Step 4: Review for survivability

After the run, ask:

- Would this evidence convince a skeptical auditor?
- Could another team reproduce it?
- Would this still make sense in 6 months?

The benchmark is passed if:
- failure points are **visible**
- assumptions are **explicit**
- gaps are **documented**, not hidden

---

## Outputs

Typical outputs include:

- a list of evidence gaps
- a list of fragile assumptions
- documentation fragments that need stabilization
- areas where automation would help
- areas where automation would **not** help

These outputs are intentionally informal.

---

## What this benchmark is not

- Not a compliance framework
- Not a regulator-approved process
- Not a certification
- Not legal advice
- Not an operational control system

It is a **stress test**.

---

## Why this matters

Many audit failures do not happen because teams lack documentation.
They happen because documentation **collapses under pressure**.

This benchmark makes that collapse visible.

---

## Optional next steps

Teams may choose to:

- stabilize documentation structure
- introduce evidence versioning
- add explicit ownership
- adopt a structured baseline (e.g. EU AI Act Layer Lite)

None of these are required to run the benchmark.

---

## Summary

This benchmark exists to answer one question:

**“What breaks first when time runs out?”**

If you can answer that, you are already ahead of most teams.


