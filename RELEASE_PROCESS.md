# Release Process

## Version 1.0 | 2026

This document defines the operational process for releasing new versions of the Fair Community License (FCL) and related institutional documents.

The objective is to ensure stability, predictability, and procedural transparency. This process operates in alignment with our Governance, Versioning Policy, and Charter.

---

## 1. Types of Releases

FCI recognizes three categories of releases based on their impact:

### 1.1 Patch Releases (v1.0.1)

Used for typographical corrections, formatting fixes, or cross-reference updates.
**Impact:** Non-substantive. These must not alter legal meaning.

### 1.2 Minor Releases (v1.1)

Used for clarifications that improve precision, structural reorganization, or improved definitions that preserve original intent.
**Impact:** Clarification. These must not introduce new commercial restrictions.

### 1.3 Major Releases (v2.0)

Used for changes to commercial boundaries, redefinition of core terms, or structural philosophical shifts.
**Impact:** Structural. These require a formal RFC process.

---

## 2. Release Workflow

### Step 1 — Proposal

A release proposal may originate from the Steward, a Maintainer, or a formal community submission. It must specify scope, rationale, and impact analysis.

### Step 2 — Internal Review

Maintainers review the proposal for consistency with the Charter and cross-variant compatibility. For Major releases, Advisory Board consultation is triggered.

### Step 3 — RFC (If Required)

Major changes must undergo a public **Request for Comments (RFC)**:

- Publication of a Public Draft.
- Minimum 30-day comment period.
- Publicly visible discussion and feedback summary.

### Step 4 — Final Text Approval

The final text is version-tagged, includes a release date, and a change summary. Once approved, the text becomes **immutable** for that specific version.

---

## 3. Publication & Integrity

Upon release:

- The version is committed to the official repository.
- A Git tag is created (e.g., `fcl-standard-v1.1`).
- A `CHANGELOG` entry is published.
- **Historical versions are preserved permanently** to ensure legal continuity.

---

## 4. Non-Retroactivity

New versions do not retroactively alter:

- Projects already licensed under previous versions.
- Rights already granted under prior releases.

Adopters must explicitly choose to upgrade to a newer version.

---

## 5. Emergency Clarifications

In the event of urgent ambiguity discovery:

- A Patch release may be issued immediately.
- The clarification **must not** expand restrictions.
- A public note must explain the specific issue addressed.

---

## 6. Institutional Documents

This Release Process also applies to updates regarding:

- Governance & Charter.
- Trademark Policy.
- Advisory Board framework.

---

## 7. Authority

Final release authority rests with the **Stewards**, as defined in `GOVERNANCE.md`. The Release Process ensures structured deliberation and transparency before any final approval.

---

**Fair Community Initiative** *Stewardship through structure.*
