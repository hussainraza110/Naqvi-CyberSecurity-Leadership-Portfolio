# Cyber Recovery Strategy

## Outcomes
Restore critical services to a known, trusted, secure, operationally validated state while minimizing customer harm and residual risk.

## Phases
1. Stabilize: contain compromise; protect backup/recovery assets.
2. Establish clean control: validate identity, privilege, keys, management planes, and recovery environment.
3. Select recovery point: assess age, integrity, malware risk, and data loss.
4. Restore foundations: identity, network segmentation, core infrastructure, logging, security tooling, dependencies.
5. Restore services in business-priority order.
6. Validate security, data reconciliation, function, and business acceptance.
7. Resume in stages with heightened monitoring and incident watch.
8. Improve: track and validate gaps.

## Recovery gates
- Scope and trust boundaries sufficiently understood.
- Recovery source/environment integrity verified.
- Trusted identity and privileged access rebuilt or verified.
- Security monitoring and controls active.
- Data integrity/reconciliation passes.
- Business owner confirms fitness for use.
- Residual risks, exceptions, and monitoring approved/documented.

## Ransomware safeguards
Keep recovery admin credentials separate from compromised paths; independently verify immutability/access; avoid restoring persistence; rebuild when eradication confidence is inadequate; prevent restored systems reconnecting to compromised management infrastructure; coordinate decisions with legal, risk, and business leaders.
