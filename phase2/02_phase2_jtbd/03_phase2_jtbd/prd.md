# Product Requirements Document (PRD) — Phase 2.4
**Project:** AI Risk Assistant for Procurement  
**Company:** Air Astana  
**Phase:** 2.4 — JTBD & PRD  
**Author:** [Akmaral and Anna]  

---

## 1. Problem Statement
Procurement officers at Air Astana spend excessive time reviewing supplier contracts due to strict aviation regulations, internal policies, and audit requirements.  
The root cause is **fear of errors and personal accountability**, which slows down contract approvals.  
Current tools and templates are insufficient because officers do not fully trust automation in a high-risk environment.

---

## 2. Job To Be Done (JTBD)
**When** reviewing supplier contracts,  
**I want** an AI assistant to highlight potential compliance risks and deviations from templates,  
**So I can** approve contracts confidently, reduce delays, and remain compliant with aviation regulations.

---

## 3. Users & Stakeholders
**Primary Users:**  
- Senior Procurement Officers

**Stakeholders:**  
- Procurement Manager  
- Legal Department  
- Compliance & Audit teams  
- IT / Digital Transformation team  
- CFO (cost/time impact)

---

## 4. Functional Requirements
1. **Contract Pre-Check:** AI scans contracts for clauses that may violate aviation regulations or internal policies.  
2. **Risk Highlighting:** Flags potentially problematic clauses with clear explanations.  
3. **Explainable Guidance:** Provides human-readable reasoning for each flagged item.  
4. **Template Comparison:** Compares new contracts against approved templates and highlights deviations.  
5. **Audit Trail:** Logs every suggestion, including references to regulations and internal rules.  
6. **Human-in-the-Loop:** AI only suggests; final approval remains with the officer.

---

## 5. Non-Functional Requirements
- **Explainability:** Recommendations must be understandable and transparent.  
- **Audit Trail:** Every AI suggestion is logged for internal and regulatory audits.  
- **Data Residency:** All data remains within Kazakhstan-compliant servers.  
- **Human-in-the-Loop:** Final decisions must remain with humans; AI cannot make autonomous approvals.  
- **Performance:** Standard contract analysis completed under 2 minutes.  
- **Reliability:** 99.9% uptime; logs maintained.

---

## 6. Success Metrics
- **Cycle Time:** Reduce average contract review time by 30%  
- **Error Rate:** Zero compliance violations due to AI suggestions  
- **Compliance Incidents:** Maintain zero audit findings  
- **User Trust:** Positive feedback from procurement officers and legal team

---

**End of PRD**
