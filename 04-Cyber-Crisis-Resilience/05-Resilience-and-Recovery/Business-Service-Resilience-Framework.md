# Business Service Resilience Framework

Map cyber risk to critical services, dependencies, impact tolerances, recovery objectives, and accountable owners.

## Service profile fields
Business service and executive owner; customer/market impact; critical processes and minimum viable service; technology, identity, data, network, facility, and supplier dependencies; RTO/RPO where applicable; maximum tolerable disruption; workarounds/capacity/backlog; recovery sequence and validation; communications; tests, exceptions, and remediation.

## Illustrative dependency register
| Service | Process | Dependencies | Recovery gate |
|---|---|---|---|
| Digital payments | Initiation and processing | Identity, payment platform, network, settlement partner | Reconcile transactions; business confirms integrity |
| Retail banking | Customer access/account servicing | Identity, core banking, API gateway, data services | Validate balances, transactions, access, channels |
| Investment services | Order and portfolio servicing | Identity, market connectivity, portfolio data, suppliers | Validate order state, data, market controls |

## Recovery principles
Restore trustworthy identity/admin control first; separate clean recovery from compromised trust paths; verify backup integrity and malware/persistence; sequence by business criticality and dependencies; validate data, controls, and functionality; obtain service-owner sign-off; monitor for recurrence.

Tests should simulate cyber conditions such as compromised credentials, unavailable dependencies, persistence, data uncertainty, and constrained staffing. Record scope, objectives, results, gaps, business sign-off, and retest evidence.
