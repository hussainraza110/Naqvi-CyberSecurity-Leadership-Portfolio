# Case 01 — Ransomware Resilience

## Context
A tabletop identifies uncertain backup integrity, recovery dependencies, and crisis decision rights for critical customer services.

## Decision
Fund prevention tools alone, recovery engineering, or a phased balanced program?

| Option | Benefit | Trade-off |
|---|---|---|
| Prevention-led | May reduce intrusion likelihood | Does not prove recovery after control failure |
| Recovery uplift | Improves continuity confidence | Requires service-owner time and cost |
| Balanced phased | Addresses both prevention and recovery | Needs sequencing and ownership |

**Recommendation:** balanced, with immediate validation of critical service recovery. Confirm clean restore points, identity/network dependencies, restore order, business acceptance, and crisis communications.

RTO/RPO must be business-approved. A backup is not recoverable until restoration is tested. Define authority for service shutdown, communication, and regulatory notification. Measure test success against RTO/RPO and validated clean recovery coverage.
