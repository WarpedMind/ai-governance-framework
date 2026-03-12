# AI Risk Tiering Model

**Version 1.0**

Maintained by **[Thomas C. Grow II](https://github.com/WarpedMind)**  
Fractional Chief AI Officer · AI Strategy & Governance · Digital Transformation  
Certified Chief AI Officer (CAIO), [World AI University](https://waiu.org)  
Charter Member & Teaching Faculty, [World AI Council](https://waicouncil.org)  
Co-founder, [MarketHack.ai](https://markethack.ai)  
*A practical framework for classifying AI use cases by risk level and applying appropriate oversight. Adapted from the EU AI Act risk classification approach and the NIST AI Risk Management Framework (AI RMF).*

---

## Why Risk Tiering Matters

Not all AI use cases carry the same risk. A spelling correction tool and an AI-assisted hiring system are both "AI" — but they require completely different governance postures. Treating them the same leads to one of two failures:

- **Over-governing low-risk tools** — creating bureaucratic friction that slows adoption and frustrates employees
- **Under-governing high-risk systems** — creating legal, ethical, reputational, and operational exposure

Risk tiering solves this by matching oversight requirements to actual risk, freeing low-risk tools to move fast while ensuring consequential systems get the scrutiny they deserve.

---

## The Four-Tier Model

### Tier 1: Low Risk

**Definition:** AI systems that assist with internal tasks, have low consequence if they produce errors, and do not involve sensitive data or consequential decisions.

**Characteristics:**
- Errors are easily caught and corrected by the user
- No sensitive, personal, or regulated data involved
- No customer-facing outputs without human review
- No decisions that materially affect people's opportunities, rights, or safety

**Examples:**
- Internal document drafting and summarization
- Code completion and review assistance
- Meeting transcription and summarization
- Research and information retrieval
- Internal chatbots for HR FAQs or IT helpdesk

**Required oversight:**
- Standard acceptable use policy compliance
- No additional approval required
- Periodic spot audits (annually)
- Employee training on responsible use

---

### Tier 2: Medium Risk

**Definition:** AI systems that produce customer-facing outputs, influence business decisions, or handle moderately sensitive data — where errors have meaningful but recoverable consequences.

**Characteristics:**
- Outputs may be seen by customers or external stakeholders
- Errors could affect customer experience, brand reputation, or business decisions
- May involve personal data, though not highly sensitive categories
- Human review occurs but may not catch every output before delivery

**Examples:**
- Marketing content generation and personalization
- Customer-facing chatbots and virtual assistants
- Sales prioritization and lead scoring
- Sentiment analysis for customer feedback
- Product recommendations

**Required oversight:**
- Designated AI Operator responsible for system performance
- Output monitoring and sampling (minimum monthly)
- Documented success metrics and drift thresholds
- Escalation path if outputs degrade
- Quarterly governance review
- Vendor assessment completed (see [Vendor AI Checklist](./vendor-ai-checklist.md))

---

### Tier 3: High Risk

**Definition:** AI systems that influence significant decisions affecting individuals' opportunities, livelihoods, finances, or access to services — or that handle sensitive regulated data.

**Characteristics:**
- Outputs directly influence consequential decisions about people
- May involve protected class data, financial data, health-adjacent data, or legal matters
- Errors have meaningful, potentially irreversible consequences for individuals
- Regulatory scrutiny is likely or emerging

**Examples:**
- AI-assisted hiring, screening, or performance evaluation
- Credit, pricing, or insurance risk scoring
- Content moderation with account or access implications
- Legal document analysis used in actual legal proceedings
- AI tools used in healthcare-adjacent contexts

**Required oversight:**
- Human approval required before any consequential action is taken
- Full audit trail of AI outputs and human decisions
- Bias and fairness testing before deployment and at regular intervals
- Legal and compliance review before deployment
- Documented escalation and override procedures
- Semi-annual governance review
- Executive sign-off for initial deployment
- Incident response plan in place

---

### Tier 4: Critical Risk

**Definition:** AI systems whose failures could cause serious harm to individuals, groups, or society — including systems that are prohibited or heavily regulated under emerging AI legislation.

**Characteristics:**
- Potential for irreversible harm to individuals or groups
- Involves safety-critical infrastructure or life-affecting decisions
- Falls within categories defined as high-risk or prohibited under the EU AI Act or equivalent frameworks
- Regulatory compliance is mandatory, not optional

**Examples:**
- Medical diagnosis or treatment recommendation systems
- AI used in criminal justice, parole, or law enforcement contexts
- Autonomous systems in physical safety contexts (transportation, industrial control)
- Real-time biometric identification in public spaces
- AI systems that manipulate behavior at scale (prohibited in most frameworks)

**Required oversight:**
- Full compliance review before any deployment
- External legal and regulatory counsel engaged
- Conformity assessment (as required by applicable regulation)
- Continuous real-time monitoring
- Board or executive leadership awareness and approval
- Documented human override capability at all times
- Regular third-party audits
- Incident response and regulatory notification procedures in place

---

## Risk Classification Worksheet

Use this worksheet to classify a new AI use case before deployment:

**Use Case Name:** _______________

**Step 1: Consequence assessment**
- Who is affected if this system produces incorrect outputs? *(Internal only / Customers / Third parties / Broad public)*
- How reversible are the consequences? *(Easily corrected / Requires effort to correct / Difficult to reverse / Irreversible)*
- What is the blast radius of a significant error? *(Individual / Team / Department / Organization / Customers / Society)*

**Step 2: Data sensitivity**
- What data does this system use or produce?
- Does it involve PII, protected class attributes, financial records, health data, or regulated information?

**Step 3: Regulatory exposure**
- Is this use case mentioned in the EU AI Act, NIST AI RMF, or applicable industry regulation?
- Does your organization's legal team need to be aware?

**Step 4: Assign tier**

| If... | Then assign... |
|---|---|
| Internal use, low consequence, no sensitive data | Tier 1 — Low |
| Customer-facing or moderate consequence | Tier 2 — Medium |
| Influences decisions about people, sensitive data | Tier 3 — High |
| Safety-critical, potentially regulated, irreversible harm potential | Tier 4 — Critical |

---

## Regulatory Reference

This model is informed by but not identical to:

**EU AI Act (2024)**  
Establishes four risk categories: Unacceptable Risk (prohibited), High Risk (heavily regulated), Limited Risk (transparency obligations), Minimal Risk (light touch). This tiering model maps roughly: Tier 4 ≈ High Risk/Unacceptable, Tier 3 ≈ High Risk, Tier 2 ≈ Limited Risk, Tier 1 ≈ Minimal Risk.

**NIST AI Risk Management Framework (AI RMF)**  
Provides a voluntary framework organized around four functions: Govern, Map, Measure, Manage. This tiering model supports the Map and Measure functions by providing a structured classification approach.

**ISO 42001**  
The emerging international standard for AI management systems. Risk classification is a core requirement of an ISO 42001-aligned AI management system.

---

## Related Documents

- [AI Readiness Scorecard](../assessment/ai-readiness-scorecard.md)
- [AI Governance Policy Template](./ai-governance-policy-template.md)
- [AI Transformation Roadmap](../strategy/ai-transformation-roadmap.md)
- [Vendor AI Assessment Checklist](./vendor-ai-checklist.md)

---

*Last updated: March 2026*
