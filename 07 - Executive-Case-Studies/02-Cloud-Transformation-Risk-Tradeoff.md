# Case 02 — Cloud Transformation Risk Trade-off

A business proposes migrating a customer-facing service for agility and scale. Dependencies include identity federation, logging, data classification, resilience, and supplier assurance.

| Option | Upside | Risk |
|---|---|---|
| Accelerate | Earlier business value | Carries control gaps into production |
| Delay entirely | More control preparation | Opportunity cost / shadow solutions |
| Phased and gated | Balances speed and readiness | Requires enforceable gates |

**Recommendation:** phased migration by workload risk. Gate launch on identity, data protection, monitoring, recovery, supplier, and incident readiness. Document shared responsibility, validate architecture, test emergency access, monitor cloud cost, and obtain risk-owner approval for exceptions.

Measures: readiness by tier, unresolved high risks, recovery evidence, logging coverage, cost variance, release lead time.
