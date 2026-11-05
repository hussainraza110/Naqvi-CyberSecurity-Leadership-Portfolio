# KPI / KRI Framework and Example Trend

Every metric record includes name, objective, type, definition, numerator/denominator, source, owner, frequency, threshold, limitations, and breach response.

## Example trend (fictional)
| Indicator | Q1 2026 | Q2 2026 | Q3 2026 | Appetite | Interpretation |
|---|---:|---:|---:|---|---|
| Privileged accounts with phishing-resistant MFA | 91% | 94% | 96% | ≥98% | Improving, remains below appetite |
| Critical internet-facing vulnerabilities remediated within 7 days | 82% | 88% | 92% | ≥95% | Improving; near limit |
| Critical-service recovery tests meeting objective | 100% | 83% | 67%* | 100% | Deteriorating; test scope matters |
| High-severity alert triage within SLA | 97% | 98% | 99% | ≥98% | Within appetite |
| Material suppliers with current assurance evidence | 92% | 91% | 92% | ≥95% | Near limit |

*Q3: 4 of 6 completed tests met full objective; two critical services remained untested or pending retest. Disclose denominator and scope.

## Metric definition examples

### Privileged authentication coverage (KRI)
- Definition: proportion of in-scope privileged identities protected by enforced phishing-resistant MFA.
- Numerator: identities with verified enforcement.
- Denominator: all in-scope privileged identities at cut-off.
- Limitation: inventory completeness and service-account treatment affect denominator.

### Critical vulnerability remediation (KPI/KRI)
- Definition: proportion of critical internet-facing vulnerabilities remediated within seven days.
- Numerator: eligible findings closed within target.
- Denominator: eligible findings due in period.
- Limitation: discovery, exploitability, compensating controls, and exceptions need visibility.

### Recovery test success (KRI)
- Definition: proportion of completed critical-service cyber recovery tests meeting recovery objectives and business validation.
- Numerator: tests meeting all criteria.
- Denominator: completed tests; separately disclose those not completed.
- Limitation: test meaningfulness depends on dependencies, data integrity, and business acceptance.

## Interpretation
Do not use improving KPI performance as proof risk is acceptable while KRIs remain above appetite. Never omit denominator or scope exclusions. Compare periods only when definitions are stable; annotate changes. Report performance and residual exposure.
