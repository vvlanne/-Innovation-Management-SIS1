# Phase 3 - Go/No-Go Executive Summary
## Project: AI Risk Assistant for Procurement (Air Astana)

### Decision
**GO - with conditions**

---

## Financial justification (ROI)

**Assumptions**
- Time saved per Procurement Officer: **10 hours/week** (assignment assumption)
- Number of users (Procurement Officers): **N = [PUT YOUR NUMBER]**
- Salary baseline: Average monthly wage in Kazakhstan (2024): **405,416 KZT** :contentReference[oaicite:4]{index=4}
- Working hours per month: **160**

**Calculation**
- Hourly rate ≈ 405,416 / 160 ≈ **2,534 KZT/hour**
- Annual hours saved per employee = 10 * 52 = **520 hours**
- Gross annual savings ≈ N * 520 * 2,534

**Estimated annual costs**
- Model usage (LLM/API): **[X]**
- Infrastructure + monitoring: **[Y]**
- Security/compliance review + controls: **[Z]**
- Training/change management: **[W]**
**Total annual cost ≈ [X+Y+Z+W]**

**Result**
- **Gross annual savings:** ~ **[ ] KZT**
- **Net annual benefit:** ~ **[ ] KZT**
- **Payback:** **[ ] months** (Net benefit / monthly costs)

---

## Governance & Ethics (Kazakhstan AI Ethics + enterprise governance)

**Key principle:** AI provides recommendations only; humans remain accountable.
Kazakhstan’s AI regulatory framework emphasizes transparency, accountability and safety. :contentReference[oaicite:5]{index=5}

### Risks and Mitigations

| Risk | Why it matters for Air Astana procurement/contracts | Mitigation / control |
|---|---|---|
| Sensitive contract data | Supplier and aviation-related contracts contain confidential terms | Keep processing in approved environment; strict access control; encryption |
| Data residency & third-party exposure | Contract text must not leak to external vendors | Use Kazakhstan-compliant hosting / on-prem; disable training on customer data |
| Hallucination / wrong interpretation | AI can suggest incorrect clause meaning | “Highlight-only” + citations to policy text; mandatory human review |
| Auditability | Auditors need to see who decided what and why | Full audit trail: input, model output, user action, timestamp |
| Accountability shift | Risk of “AI decided” mindset | UI and policy: AI = advisor; final approver = human |
| Explainability | Decisions must be defensible | Provide reason + reference snippet for every flag |

---

## Conditions to proceed (must-have)
1. **Human-in-the-loop** for all approvals (AI cannot approve contracts)
2. **Audit trail** enabled by default
3. **Data handling rules** (access control, retention, residency boundary)
4. Pilot scope limited to **procurement contracts for IT/digital initiatives**, then scale

---

## Recommendation
Proceed with a **90-day pilot** to validate:
- cycle time reduction
- reduction in manual checks
- user trust/adoption
- zero increase in compliance incidents
