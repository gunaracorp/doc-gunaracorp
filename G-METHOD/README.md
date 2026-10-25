# G METHOD™ — Master Workstream

**Status:** Working draft / source reconciliation in progress  
**Owner/author attribution:** Gugun Gunara / GUNARACORP (as supplied by project owner)  
**Version:** 1.0.0-draft  
**Last updated:** 2026-10-26

## Purpose

This directory is the controlled working area for the G Method™ and UMEA architecture. It separates owner-provided concepts from hypotheses and implementation decisions. It does not claim that every registry has been validated against the original source documents.

## Core concepts currently evidenced in the working notes

- **G Method™** — The Gugun Organizational & Enterprise Architecture Method (G = Gunara).
- **UMEA** — Universal Minimum Enterprise Architecture.
- **UMEA Master Matrix™** — organizational intelligence and decision-support matrix.
- **21 critical organizational functions × 6 levels × documentation tiers** as a proposed architecture.
- Matrix attributes: **C/O/E/R/K/S/M** = Criticality, Ownership, Evidence, Risk, KPI, SOP, Maturity.
- Documentation tiers noted in the working notes: **D-10, D-21, D-39, D-75, D-165**.
- Level labels noted in the working notes: **UMEA-03, UMEA-05, UMEA-07, UMEA-10, UMEA-15, UMEA-21**.

These names and counts are preserved as working inputs. Their exact definitions, inventories, and applicability must be reconciled against the owner's canonical source files before being marked approved.

## Workstream status

| Workstream | Status | Exit condition |
|---|---|---|
| 1. Reconcile original sources | In progress | Canonical source filenames, versions, dates, and conflicts recorded |
| 2. Lock master registries | Not approved | 21 function names, 6 level definitions, and each tier inventory verified against sources |
| 3. Build UMEA Master Matrix | Schema draft | Applicability rules, evidence requirements, scoring, and ownership approved |
| 4. Derived documents and quality gates | Draft | Templates pass documented quality checks |
| 5. Prototype and pilot | Not run | At least one real case tested, results and changes recorded |

## Required canonical sources

The working notes refer to:
- `JEP3_39_Dokumen_Bisnis_Kelas_Dunia.md`
- `pga-165-completed.md`
- A source export named `berlian-gunara-hukum-usaha.md`

Do not treat a similarly named document as equivalent without checking its contents and version. If a source cannot be located in the repository, record it as missing; do not reconstruct its exact inventory from memory.

## Governance rules

1. Preserve the owner's original terminology and structure.
2. Label every item as **SOURCE-VERIFIED**, **OWNER-DECISION**, **INFERENCE**, or **PROPOSED**.
3. Never invent the 21 function names or the full document inventory.
4. Keep scoring formulas provisional until tested on real cases.
5. Record source file, section/page, version, date, and reviewer for each canonical registry item.
6. Keep confidential methods and client data out of public repositories unless explicitly approved.
7. A trademark symbol in this repository is a project designation, not proof of registration or a legal conclusion about exclusivity.

## Files

- `01_SOURCE_RECONCILIATION_REGISTER.md` — source inventory and discrepancy log.
- `02_REGISTRY_LOCK_SPEC.md` — rules for canonical registry approval.
- `03_UMEA_MATRIX_SCHEMA.csv` — matrix record schema.
- `04_MATRIX_DECISION_RULES.md` — provisional decision and evidence rules.
- `05_QUALITY_GATES.md` — quality control gates for deliverables.
- `06_PILOT_PROTOCOL.md` — protocol for real-case validation.
- `registries/21_FUNCTIONS_REGISTRY.csv` — intentionally unpopulated canonical function names pending source verification.
- `registries/6_LEVELS_REGISTRY.csv` — level labels captured; definitions pending verification.
- `registries/DOCUMENT_TIERS_REGISTRY.csv` — tier labels captured; inventories pending verification.
