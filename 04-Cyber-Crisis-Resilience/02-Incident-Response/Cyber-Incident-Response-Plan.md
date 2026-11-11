# Cyber Incident Response Plan

## Lifecycle
1. Prepare: roles, playbooks, telemetry, contact trees, exercises, evidence handling.
2. Detect/report: validate signal and preserve initial evidence.
3. Analyze: scope, attack path, identities/assets/data, confidence, business impact.
4. Contain: proportionate actions to prevent spread/harm; document trade-offs.
5. Eradicate: remove persistence, remediate weaknesses, revoke/reset compromised credentials, verify integrity.
6. Recover: restore known-good sources, validate identity/dependencies, monitor recurrence, obtain business sign-off.
7. Learn: review incident and validate corrective actions.

## Illustrative severity
| Level | Example | Governance |
|---|---|---|
| SEV-1 Critical | Critical service disrupted, broad privileged compromise, likely material impact | Crisis activation, executive updates |
| SEV-2 High | Significant unit or sensitive data affected; credible critical-service path | CISO-led; assess crisis criteria |
| SEV-3 Moderate | Limited, contained impact | Incident team, routine executive visibility |
| SEV-4 Low | Low impact, no material compromise evidence | Owner handling and tracking |

Severity follows actual impact and plausible trajectory—not alert criticality alone.

## Evidence
Preserve relevant logs, volatile evidence, endpoint artifacts, identity events, and network telemetry when feasible. Record collector, method, time source, storage, access, and integrity hash where appropriate. Maintain chain of custody when evidence may be used for investigation/legal purposes. Coordinate urgent containment with collection and record evidence trade-offs. Follow applicable legal, privacy, and retention rules.

## Ransomware considerations
Determine whether encryption, exfiltration, extortion, or destructive activity is confirmed/suspected/unsubstantiated. Isolate affected systems under approved procedures; protect backups and recovery credentials; establish clean trust paths; investigate initial access, persistence, lateral movement, and credential exposure. Legal and executive leadership decide notification, negotiation, and other legally sensitive matters with qualified counsel. This plan does not prescribe ransom payment. Do not make unsupported claims about data theft or recovery.

## Closure
Containment/eradication evidenced; recovery and business validation complete or accepted; evidence retained; stakeholders informed as required; residual risk/actions assigned; review scheduled.
