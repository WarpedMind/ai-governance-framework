# Vendor AI Assessment Checklist

**Version 1.0**

Maintained by **[Thomas C. Grow II](https://github.com/WarpedMind)**  
Fractional Chief AI Officer · AI Strategy & Governance · Digital Transformation  
Certified Chief AI Officer (CAIO), [World AI University](https://waiu.org)  
Charter Member & Teaching Faculty, [World AI Council](https://waicouncil.org)  
Co-founder, [MarketHack.ai](https://markethack.ai)  
*Due diligence questions for evaluating third-party AI tools and vendors before organizational adoption. Use alongside your standard vendor security and procurement review — not as a replacement for it.*

---

## How to Use This Checklist

Complete this assessment before approving any new AI vendor for organizational use. The appropriate depth of review scales with your [Risk Tier](./risk-tiering-model.md):

- **Tier 1 (Low Risk):** Sections 1 and 2 minimum
- **Tier 2 (Medium Risk):** Sections 1–4
- **Tier 3 (High Risk):** All sections; legal review recommended
- **Tier 4 (Critical Risk):** All sections; external counsel and compliance team required

**Vendor Name:** _______________  
**Tool / Product:** _______________  
**Proposed Use Case:** _______________  
**Risk Tier:** _______________  
**Assessment Date:** _______________  
**Assessed By:** _______________

---

## Section 1: Data Handling & Privacy

| # | Question | Response | Notes |
|---|---|---|---|
| 1.1 | What data is collected when using this tool? | | |
| 1.2 | Where is data stored, and in which regions? | | |
| 1.3 | Is data transmitted to third parties or subprocessors? If so, who? | | |
| 1.4 | Is our data used to train or fine-tune the vendor's models? | | |
| 1.5 | Can we opt out of data being used for model training? | | |
| 1.6 | What is the vendor's data retention policy? Can we request deletion? | | |
| 1.7 | Is the vendor compliant with applicable privacy regulations? (GDPR, CCPA, HIPAA if relevant) | | |
| 1.8 | Does the vendor offer a Data Processing Agreement (DPA)? | | |
| 1.9 | What happens to our data if we terminate the contract? | | |

**Section 1 Assessment:** ☐ Pass &nbsp;&nbsp; ☐ Conditional &nbsp;&nbsp; ☐ Fail  
**Notes:** _______________

---

## Section 2: Model Transparency & Explainability

| # | Question | Response | Notes |
|---|---|---|---|
| 2.1 | What type of AI model powers this tool? (LLM, ML classifier, rules-based, etc.) | | |
| 2.2 | Can the vendor explain how the model produces its outputs? | | |
| 2.3 | What training data was used? Is it documented? | | |
| 2.4 | Has the model been tested for bias? What were the results? | | |
| 2.5 | How does the vendor handle model hallucinations or errors? | | |
| 2.6 | Does the vendor publish model cards or system cards? | | |
| 2.7 | How frequently is the model updated, and how are users notified of changes? | | |
| 2.8 | Are there known failure modes or use cases the model is not suitable for? | | |

**Section 2 Assessment:** ☐ Pass &nbsp;&nbsp; ☐ Conditional &nbsp;&nbsp; ☐ Fail  
**Notes:** _______________

---

## Section 3: Security & Reliability

| # | Question | Response | Notes |
|---|---|---|---|
| 3.1 | What security certifications does the vendor hold? (SOC 2, ISO 27001, etc.) | | |
| 3.2 | Has the vendor completed a third-party penetration test? When? | | |
| 3.3 | What is the vendor's incident response process for security breaches? | | |
| 3.4 | How quickly are we notified in the event of a breach affecting our data? | | |
| 3.5 | What is the vendor's documented uptime SLA? | | |
| 3.6 | What is the vendor's historical uptime over the past 12 months? | | |
| 3.7 | Is there a status page for real-time system health monitoring? | | |
| 3.8 | What is the process for reporting a security vulnerability to the vendor? | | |

**Section 3 Assessment:** ☐ Pass &nbsp;&nbsp; ☐ Conditional &nbsp;&nbsp; ☐ Fail  
**Notes:** _______________

---

## Section 4: Governance & Compliance

| # | Question | Response | Notes |
|---|---|---|---|
| 4.1 | Does the vendor have a published AI ethics or responsible AI policy? | | |
| 4.2 | Is the vendor compliant with or preparing for EU AI Act requirements? | | |
| 4.3 | Does the vendor align with any recognized AI governance frameworks? (NIST AI RMF, ISO 42001) | | |
| 4.4 | Does the vendor have a process for users to contest or appeal AI-generated outputs? | | |
| 4.5 | How does the vendor handle requests from regulators or law enforcement for our data? | | |
| 4.6 | What is the vendor's policy on prohibited uses of their AI system? | | |
| 4.7 | Has the vendor been involved in regulatory actions, lawsuits, or public incidents related to AI? | | |
| 4.8 | Does the vendor conduct ongoing bias and fairness audits? | | |

**Section 4 Assessment:** ☐ Pass &nbsp;&nbsp; ☐ Conditional &nbsp;&nbsp; ☐ Fail  
**Notes:** _______________

---

## Section 5: Commercial & Exit Terms

| # | Question | Response | Notes |
|---|---|---|---|
| 5.1 | What are the contract term and renewal conditions? | | |
| 5.2 | Are there volume or usage caps that could affect operations? | | |
| 5.3 | What happens to our data and outputs if the vendor is acquired or shuts down? | | |
| 5.4 | What is the data export process if we switch vendors? | | |
| 5.5 | Are there lock-in provisions that would make switching costly? | | |
| 5.6 | Does the vendor indemnify us for harms caused by their AI system's outputs? | | |
| 5.7 | What liability limitations does the vendor's contract include? | | |
| 5.8 | Is pricing stable, or subject to change? Under what conditions? | | |

**Section 5 Assessment:** ☐ Pass &nbsp;&nbsp; ☐ Conditional &nbsp;&nbsp; ☐ Fail  
**Notes:** _______________

---

## Overall Assessment Summary

| Section | Result |
|---|---|
| 1. Data Handling & Privacy | |
| 2. Model Transparency & Explainability | |
| 3. Security & Reliability | |
| 4. Governance & Compliance | |
| 5. Commercial & Exit Terms | |

**Overall Recommendation:**  
☐ **Approve** — Vendor meets requirements for proposed use case at assigned risk tier  
☐ **Approve with Conditions** — Vendor approved subject to the following requirements: _______________  
☐ **Defer** — Additional information needed before decision: _______________  
☐ **Reject** — Vendor does not meet requirements. Reason: _______________

**Approved By:** _______________  
**Date:** _______________  
**Next Review Date:** _______________

---

## Red Flags — Automatic Escalation Required

Escalate to legal and AI governance leadership immediately if any of the following are true:

- Vendor cannot provide a Data Processing Agreement
- Vendor confirms our data is used for model training with no opt-out
- Vendor has no documented security certifications for Tier 3+ use cases
- Vendor has been subject to regulatory action related to AI in the past 24 months
- Contract terms prevent data export or deletion upon termination
- Vendor cannot explain how their model produces outputs for high-stakes use cases
- Vendor's terms include unlimited liability waivers for AI output harms

---

## Related Documents

- [Risk Tiering Model](./risk-tiering-model.md)
- [AI Governance Policy Template](./ai-governance-policy-template.md)
- [AI Readiness Scorecard](../assessment/ai-readiness-scorecard.md)
- [AI Transformation Roadmap](../strategy/ai-transformation-roadmap.md)

---

Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) — use freely with attribution.

*Last updated: March 2026*
