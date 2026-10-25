# Master Registry Lock Specification

## Approval labels

- **SOURCE-VERIFIED** — directly supported by a canonical source with a recorded section/page.
- **OWNER-DECISION** — explicitly approved by the method owner where sources are silent or conflicting.
- **INFERENCE** — reasoned interpretation; never presented as an original source statement.
- **PROPOSED** — a new design suggestion awaiting approval.
- **RETIRED** — preserved for traceability but no longer active.

## Registry lock criteria

### A. 21 critical organizational functions
Each record must include stable ID, canonical name, source wording, normalized wording (if different), definition, scope/in-scope examples, exclusions, upstream/downstream dependencies, accountable owner, evidence reference, status, and approval date. Do not populate canonical names from generic business frameworks.

### B. Six UMEA levels
Capture the original label exactly (currently noted as UMEA-03, UMEA-05, UMEA-07, UMEA-10, UMEA-15, UMEA-21), original definition, sizing or selection rule, applicability, transition criteria, exceptions, evidence reference, and approval. The numeric suffix must not be interpreted without source evidence.

### C. Documentation tiers
For each of D-10, D-21, D-39, D-75, D-165, capture tier purpose, inclusion criteria, complete document inventory, mandatory/conditional status, dependencies, owner, version, and source evidence. Validate counts against unique document IDs; aliases do not count as distinct documents unless explicitly defined by the source.

## Release gate

A registry is LOCKED only when:
1. Every canonical record has provenance.
2. Counts reconcile with the source.
3. Duplicates and aliases are explained.
4. Conflicts are resolved by explicit owner decision.
5. A reviewer other than the initial compiler checks the inventory.
6. A versioned snapshot and change log are committed.
