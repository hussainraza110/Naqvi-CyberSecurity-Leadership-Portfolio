# Worked Investment Business Case — Privileged Access Uplift

> Fictional example. Figures, estimates, and scenario data are illustrative.

## Decision summary
**Request:** Approve PKR 42m implementation funding and PKR 13m annual operating cost for a phased privileged access management (PAM) and identity threat protection uplift.  
**Sponsor:** Chief Information Security Officer.  
**Business owner:** Technology Operations.  
**Decision:** Approve subject to staged procurement, integration design, and service acceptance.

## Risk statement
Compromised administrator credentials or excessive standing privileges could enable unauthorized access to critical infrastructure and customer-facing services, resulting in service disruption, data exposure, fraud, and regulatory scrutiny. Existing controls are assumed to have inconsistent privileged session coverage and incomplete just-in-time access.

## Options
| Option | 3-year TCO (PKR m) | Assessment |
|---|---:|---|
| A — Retain current controls | 0 incremental | Leaves documented exposure and operational inconsistency |
| B — PAM platform + phased onboarding | 81 | Recommended balance of risk reduction, control evidence, and operating model |
| C — Fully managed service | 96 | Faster coverage potential; higher recurring cost and provider dependency |

TCO for Option B = 42 implementation + 13×3 recurring = **PKR 81m**. This simplified estimate excludes inflation, tax, and discounting; finance should validate.

## Delivery outline
1. Inventory privileged identities and critical platforms.
2. Establish architecture, vaulting, session control, break-glass, and access approval patterns.
3. Pilot on high-risk infrastructure and validate operational workflows.
4. Phase onboarding by criticality and application owner readiness.
5. Test recovery, emergency access, monitoring, and service handover.

## Illustrative success measures
- 90% of in-scope privileged accounts managed by end of year one.
- 100% of Tier-0 privileged sessions recorded or subject to documented compensating control.
- Reduce standing privileged access by 70% from validated baseline.
- Quarterly recertification completion ≥ 98%.
- Emergency access test completed successfully each quarter.

## Benefits and limitations
Expected benefits are reduced exposure, stronger traceability, faster investigations, and more consistent access governance. No guaranteed financial loss avoidance is claimed. Any modeled avoided-loss estimate should be shown separately with probability, impact, and confidence assumptions.

## Key risks / mitigations
| Risk | Mitigation |
|---|---|
| Application compatibility | Pilot, exception register, and phased onboarding |
| Operational friction | Role-based workflows, service-owner engagement, training |
| Vendor concentration | Exit plan, export requirements, architecture review |
| Coverage overstated | Reconcile discovered identities against authoritative inventory |

## Approval conditions
Finance validates TCO and payment profile; architecture approves design; risk owner confirms residual-risk position; delivery lead reports monthly; benefits review occurs 90 and 180 days after operational acceptance.
