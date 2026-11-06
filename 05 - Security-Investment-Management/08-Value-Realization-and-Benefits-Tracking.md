# Value Realization and Benefits Tracking

## Benefits categories
1. **Risk outcome:** reduced likelihood, impact, exposure, or residual risk.
2. **Operational outcome:** faster detection, containment, recovery, or access review.
3. **Compliance outcome:** evidence completeness and remediation timeliness.
4. **Financial outcome:** verified cost reduction, cost avoidance, or capacity release.
5. **Enablement:** safer product delivery or business capability.

## Benefits register
| Benefit ID | Initiative | Baseline | Target | Measure / source | Owner | Frequency |
|---|---|---|---|---|---|---|
| BEN-01 | PAM | % managed privileged accounts established at discovery | ≥90% in scope by Y1 end | PAM inventory / CMDB reconciliation | IAM owner | Monthly |
| BEN-02 | Detection | Median time to triage from prior 2 quarters | 25% reduction | SIEM / incident records | SOC lead | Monthly |
| BEN-03 | Resilience | Recovery test success and actual recovery time | Meet approved RTO/RPO for critical services | Exercise and recovery evidence | Service owner | Quarterly |
| BEN-04 | Data protection | Known sensitive repositories classified | ≥85% high-risk repositories by Y2 | Discovery / data inventory | Data owner | Quarterly |
| BEN-05 | Exposure | Critical exploitable exposure backlog | 50% reduction from validated baseline | Exposure platform / ticketing | Infrastructure lead | Monthly |

Targets are illustrative and should be calibrated after baselining.

## Measurement rules
- Establish baseline before deployment or use a documented proxy.
- Define numerator, denominator, scope, exclusions, source, and owner.
- Separate output (e.g., agents deployed) from outcome (e.g., exposure reduced).
- Validate data quality and prevent double counting.
- Review at 30/90/180 days after launch and quarterly thereafter.
- Record benefits not achieved, causes, corrective actions, and accountable owner.

## Benefits status
Green = target on trajectory with evidence; Amber = material variance or data uncertainty; Red = outcome missed or risk remains outside appetite. Status is not a substitute for the underlying metric.
