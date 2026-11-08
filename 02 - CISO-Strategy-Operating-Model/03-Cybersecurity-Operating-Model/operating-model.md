# Cybersecurity Operating Model

**Portfolio project:** Folder 02 · **Case:** Meridian Financial Group (fictional) · **Audience:** CISO, executive leadership, CIO/CTO, CRO, business-unit and service owners.

All headcount, budgets, ratios, service levels and timelines are illustrative assumptions for the fictional case. Validate against the real organization, its obligations and its capacity before use.

---

## 1. Purpose

The strategy blueprint says *what* Meridian wants from cybersecurity. This document says *how the function is organized and works* so that the strategy is delivered: who does what, where decisions sit, what is sourced externally, and how security services reach the business.

## 2. Design principles

| # | Principle | Practical consequence |
|---|---|---|
| 1 | Business owners own risk; security enables and challenges | Service owners accept risk within delegated authority; the CISO advises and escalates |
| 2 | Organize around services, not tools | Each capability has an owner, a service definition and measures |
| 3 | Federated, not purely central | Central standards and platforms, with security partners embedded where change happens |
| 4 | Separate running controls from judging them | Operations and engineering are distinct from risk oversight and assurance |
| 5 | Buy volume, keep judgment | Source repeatable 24x7 work; keep architecture, risk decisions and incident leadership in-house |
| 6 | Scale with the change portfolio | Security engagement is triggered by risk tier, not by ticket volume |

## 3. Model: federated hub with embedded partners

**Hub (central security function).** Sets strategy, policy, architecture patterns and shared platforms; runs security operations, identity and resilience services; provides assurance and reporting.

**Spokes (business and technology units).** Own service risk and operate day-to-day controls. A small team of business security partners sits alongside the three business lines and the technology delivery organization to bring security in early and translate risk into business terms.

**Why not fully central?** It engages late and becomes a bottleneck across 70+ active initiatives. **Why not fully decentralized?** Unit-level inconsistency is already a stated current-state problem (see enterprise profile).

## 4. Organization (illustrative: 95 FTE)

| Function | FTE | Core responsibility |
|---|---:|---|
| Office of the CISO, strategy and metrics | 4 | Strategy, planning, reporting, board and executive interface |
| Governance, risk and compliance | 12 | Policy, risk assessment, control assurance, exceptions, audit liaison |
| Security architecture and engineering | 12 | Patterns, design authority input, secure platform engineering |
| Identity and access (including privileged access) | 12 | Identity lifecycle, privileged access, recertification |
| Security operations and response | 26 | Monitoring, detection engineering, triage, incident response |
| Application and cloud security | 10 | Secure delivery, cloud guardrails, code and configuration review |
| Third-party security | 6 | Supplier tiering, assessments, concentration monitoring |
| Cyber resilience and crisis readiness | 5 | Recovery validation, tabletop exercises, crisis playbooks |
| Business security partners | 6 | Embedded advice for business lines and delivery teams |
| Awareness and workforce enablement | 2 | Role-based training, phishing and culture programmes |
| **Total** | **95** | |

## 5. Service catalogue (extract)

| Service | Primary customers | Owner | Illustrative service measure |
|---|---|---|---|
| Security architecture review | Delivery teams | Security architecture lead | Material initiatives engaged before design sign-off |
| Risk assessment and treatment tracking | Service owners | GRC lead | High risks with named owner and dated plan |
| Identity and privileged access | All units | Identity lead | Privileged access recertified on schedule |
| Detection and response | Business, executives | Security operations lead | Time to triage and contain by incident severity |
| Cloud and application guardrails | Engineering teams | Application/cloud lead | Critical workloads meeting baseline patterns |
| Supplier security assurance | Procurement, service owners | Third-party lead | Critical suppliers assessed within cycle |
| Recovery and crisis readiness | Critical service owners | Resilience lead | Critical services exercised against impact tolerances |
| Executive risk reporting | Board, executives | Office of the CISO | Decisions requested are tracked to closure |

Each service has a one-page definition: scope, how to request it, what the customer must provide, service level, escalation route and cost model.

## 6. Three lines of defence

| Line | Who | Security role |
|---|---|---|
| First | Business units, technology and product teams, plus security engineering and operations | Own and operate controls |
| Second | Governance, risk and compliance; Enterprise Risk | Set the framework, challenge, monitor and report |
| Third | Internal Audit | Independent assurance to the Board |

**The tension.** A CISO organization usually runs controls (first line) and oversees them (second line). Meridian handles this by keeping engineering and operations separate from governance, risk and compliance in reporting and objectives, by routing control-effectiveness findings through Enterprise Risk and Internal Audit, and by never letting the same team design a control and report on whether it works.

## 7. Sourcing strategy

| Capability | Approach | Rationale |
|---|---|---|
| 24x7 monitoring, first-line triage | Hybrid: managed provider for tier 1, in-house for tier 2/3 and detection engineering | Round-the-clock volume is costly to staff; detection quality and escalation judgment stay internal |
| Penetration testing and red team | External, rotated providers | Independence and breadth of skills |
| Incident response retainer | External retainer plus internal incident command | Surge capacity without ceding decision authority |
| Architecture, risk decisions, crisis leadership | In-house | Business context and accountability cannot be outsourced |
| Specialist skills (forensics, OT/ICS where relevant) | Retainer or on-demand | Low frequency, high skill |

Provider oversight: named internal owner, contractual service levels, quarterly performance review, exit plan and concentration check.

## 8. Operating rhythm

| Cadence | Forum or activity | Output |
|---|---|---|
| Daily | Operations hand-over and incident stand-up | Active incidents, priorities |
| Weekly | CISO leadership team | Delivery, capacity, escalations |
| Monthly | Cyber Risk Steering Committee; Security Design Authority | Risk treatment decisions, architecture exceptions |
| Quarterly | Board Risk Committee report; resilience forum; supplier review | Board decisions, exercise results |
| Annually | Strategy refresh; capability reassessment; budget cycle | Updated roadmap and targets |

Decision rights and escalation triggers follow the governance model in folder `04`.

## 9. Interfaces

| Partner | What security needs | What security provides |
|---|---|---|
| Enterprise Risk (CRO) | Common risk language, appetite | Cyber risk scenarios and treatment status |
| CIO / CTO | Early sight of change, shared platforms | Patterns, standards, guardrails |
| Procurement and Legal | Supplier terms, notification clauses | Supplier risk tiers and assessment results |
| Business continuity and operations | Service impact tolerances | Cyber recovery requirements and test results |
| Internal Audit | Independence | Evidence and timely remediation |
| Finance | Budget visibility | Investment cases tied to risk reduction |

## 10. Transition (illustrative, 12 months)

1. **Months 0–3:** confirm service owners, publish service definitions, appoint business security partners to the highest-risk units.
2. **Months 3–6:** separate engineering and operations from governance reporting lines; stand up managed tier-1 monitoring with a defined exit plan.
3. **Months 6–9:** embed security triggers in the change process; start quarterly service reviews.
4. **Months 9–12:** assess whether the model reduces late engagement and clarifies risk ownership; adjust staffing and sourcing.

## 11. Risks to the model

| Risk | Mitigation |
|---|---|
| Embedded partners drift into business-unit priorities | Dotted line to the CISO; shared objectives; rotation |
| Managed provider degrades detection quality | Detection engineering kept in-house; quality sampling; service-level credits |
| Talent scarcity delays the build | Phase hiring by risk; use retainers for peaks; invest in internal progression |
| Federated model creates inconsistent practice | Common standards, design authority and a single reporting format |
| Over-engineering the structure | Revisit after twelve months against outcomes, not org-chart elegance |

## 12. How success is judged

Success is shown by outcomes defined in the strategy blueprint and the KPI/KRI framework: earlier security involvement in material change, clearer risk ownership, timely risk decisions, and recovery of critical services within impact tolerances, not by headcount or tool counts.
