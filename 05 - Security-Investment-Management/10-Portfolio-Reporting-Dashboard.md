# Portfolio Reporting Dashboard

## Executive dashboard specification
**Audience:** CISO, CFO, CRO, CIO, Board / Risk Committee.  
**Reporting period:** monthly operational view; quarterly executive view.

### Core tiles
- Approved portfolio value (PKR m)
- Actual spend, committed spend, and estimate at completion
- Initiatives by delivery status
- Initiatives with risk outcomes on track / at risk / missed
- Mandatory actions overdue
- Benefits evidence completeness
- Top dependencies and decisions required

### Suggested indicator definitions
| Indicator | Definition | RAG guidance |
|---|---|---|
| Budget variance | (EAC − approved budget) / approved budget | Green ≤5%; Amber >5% to 10%; Red >10% |
| Milestone variance | Forecast milestone date vs baseline | Green ≤10 business days; Amber 11–30; Red >30 |
| Risk outcome | Evidence of target risk reduction | Green on trajectory; Amber uncertain / delayed; Red missed |
| Mandatory remediation | Count past due | Green 0; Red ≥1 (escalate) |
| Benefits evidence | Benefits with current evidence / benefits due | Green ≥90%; Amber 75–89%; Red <75% |

Thresholds are illustrative and require organizational approval.

### Executive narrative
1. **What changed:** material risk, spend, schedule, scope, or benefits movement.
2. **Why it matters:** affected business service, exposure, or strategic outcome.
3. **Decision required:** explicit decision, owner, and deadline.
4. **Management action:** mitigation and next checkpoint.

### Dashboard design principles
Use trend and exception views; do not bury mandatory items in aggregate scores. Display the denominator and reporting date. Keep risk reduction distinct from financial savings. Every red or amber indicator should have an accountable owner and action.
