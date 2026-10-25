# Source Reconciliation Register

**Status:** IN PROGRESS  
**Rule:** Do not mark a source verified based only on a filename or prior mention.

| ID | Expected source | Current evidence | Status | Required action |
|---|---|---|---|---|
| SRC-001 | `JEP3_39_Dokumen_Bisnis_Kelas_Dunia.md` | Referenced in prior project notes; canonical content not yet verified in this repository | MISSING / UNVERIFIED | Locate exact file, record version/date/hash, inspect all 39 document entries |
| SRC-002 | `pga-165-completed.md` | Referenced in prior project notes; canonical content not yet verified in this repository | MISSING / UNVERIFIED | Locate exact file, record version/date/hash, inspect all 165 document entries |
| SRC-003 | `berlian-gunara-hukum-usaha.md` | Identified as a source export in project context | TO INSPECT | Compare terms, counts, and chronology against SRC-001 and SRC-002 |
| SRC-004 | `PGA165_Digiman_TopManajemen (1).md` | Similar filename mentioned in library context; equivalence unconfirmed | CANDIDATE ONLY | Compare contents; do not silently substitute |

## Discrepancy log

| ID | Issue | Impact | Resolution owner | Status |
|---|---|---|---|---|
| DIS-001 | Exact definitions of the six UMEA level labels are not verified | Risk of designing the wrong applicability logic | Method owner | OPEN |
| DIS-002 | Canonical list of 21 functions is not verified | Registry must remain unpopulated | Method owner | OPEN |
| DIS-003 | Full inventories for D-10, D-21, D-39, D-75, D-165 are not verified | Document generator cannot be locked | Method owner | OPEN |
| DIS-004 | UMI scoring formula/weights have not been validated | Do not publish as validated score | Method owner + pilot reviewer | OPEN |

## Source record template

For every source, capture: exact filename, repository/location, author, version, creation/update date, checksum if available, scope, extracted claims, contradictions, and approval status.
