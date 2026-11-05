# Post-Incident Review & Improvement Plan

## Objectives
Understand the event and response, identify systemic causes/control gaps, improve resilience, and validate corrective action. Keep the review blameless while maintaining control ownership.

## Review structure
1. Executive summary and impact
2. Timeline from detection to stand-down
3. Attack path and confidence
4. Affected services/data/customers/third parties
5. Response decisions, rationale, alternatives
6. What worked / did not work
7. Root and contributing causes
8. Recovery versus objectives
9. Communications and coordination
10. Corrective actions and validation

## Illustrative backlog
| Finding | Action | Owner | Due | Closure evidence |
|---|---|---|---|---|
| Identity trust may affect recovery | Separate/validate recovery admin identities | CIO/IAM | 60 days | Independent access-path test |
| Service dependency map incomplete | Map critical service dependencies | COO/Architecture | 90 days | Approved maps |
| Recovery test omitted reconciliation | Add data reconciliation and business sign-off | Service owners | Next cycle | Test evidence |
| Decision records inconsistent | Standardize log and secure collaboration | Crisis Manager | 30 days | Exercise validation |
| Supplier escalation slow | Refresh contacts and test escalation | Procurement | 45 days | Supplier exercise record |

Durations are fictional. Actions require an observable outcome, one accountable owner, due date, dependencies, closure evidence, and validation.
