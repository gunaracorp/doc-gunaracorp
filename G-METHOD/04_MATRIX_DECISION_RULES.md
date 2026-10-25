# UMEA Master Matrix — Provisional Rules

**Status:** PROPOSED; requires method-owner approval and pilot testing.

## 1. Applicability before scoring
Determine whether a function/document relationship applies to the selected organizational level and tier before assigning maturity. Use `APPLICABLE`, `CONDITIONAL`, `NOT_APPLICABLE`, or `UNRESOLVED`. Every conditional or not-applicable result requires a rationale and provenance.

## 2. C/O/E/R/K/S/M evidence fields
- **C — Criticality:** business/institutional consequence if absent or ineffective; record rationale and rating scale.
- **O — Ownership:** one accountable role; contributors may be many, accountability must be explicit.
- **E — Evidence:** objective artifact or observable proof, with source, date, and reviewer.
- **R — Risk:** linked risk record, impact, likelihood, controls, and residual risk where available.
- **K — KPI:** measure, definition, owner, baseline, target, frequency, and source.
- **S — SOP:** controlled procedure, version, process owner, and review date.
- **M — Maturity:** scored only after scale definitions and evidence thresholds are approved.

## 3. No unsupported score
Do not calculate an overall UMI/UMEA score until the scale, weights, missing-data treatment, aggregation method, and minimum evidence requirements are explicitly approved and tested. Never silently treat missing evidence as zero or as full compliance.

## 4. Decision trace
Every material decision records the input evidence, rule applied, result, rationale, reviewer, date, and any override. Overrides require a named approver and expiry/review date.

## 5. Escalation
- Missing source definition → `UNRESOLVED`.
- Conflicting source definitions → log discrepancy; no silent reconciliation.
- High-impact risk without owner/evidence → escalate to governance owner.
- Scoring disagreement → preserve both assessments and document adjudication.
