# AI Use-Case Assessment v0.2

**A lightweight pre-implementation assessment for practical AI governance**

**Author:** Rakesh Randeria  
**Version:** 0.2

## Purpose

Use this assessment before an AI use case moves from idea or experimentation into operational use. It helps business, technology, project, risk and governance teams identify issues early and make a deliberate, proportionate and owned decision.

This is a practical governance aid, not legal advice and not a substitute for privacy, security, legal, procurement, records-management or formal risk assessments where those are required.

## Core assessment model

**Use Case -> Data Classification -> Platform -> Impact -> Controls -> Decision -> Review**

## 1. Use-case profile

- Use-case name:
- Business owner:
- Assessment owner:
- AI product / platform:
- Proposed users:
- Assessment date:
- Review date / trigger:

### Problem and intended outcome

1. What problem or opportunity are we addressing?
2. Why is AI appropriate? Could the outcome be achieved more simply without AI?
3. What measurable benefit is expected - time, cost, quality, customer experience, risk reduction or new capability?
4. How will success be measured?

## 2. Data classification and information handling

### Start with the organisation's existing classification

AI governance should extend - not replace - existing information classification and data-handling requirements.

Before assessing the AI use case, identify the classification of the information involved and confirm whether that class of information is permitted in the proposed AI platform.

Refer to your organisation's **Data Classification, Data Loss Prevention (DLP), Information Security, Privacy and Acceptable Use policies**. If you are unsure how information is classified or whether it may be processed by an AI service, **check with your local IT, Information Security, Privacy or Risk team before proceeding**.

### Illustrative model only

| Example classification | Typical information | AI handling starting point |
|---|---|---|
| Public | Published information, marketing material | Generally suitable for approved AI tools |
| Internal | Internal operational information | Approved tools, subject to organisational policy |
| Confidential | Commercial terms, sensitive internal information | Vetted/enterprise tools only; confirm controls |
| Restricted / Regulated | PII, financial, health, regulated or highly sensitive information | Do not use without explicit organisational approval |

**Important:** This is an example only. Always use your organisation's existing classification scheme and policies where they exist.

### Assessment questions

1. What is the highest organisational data classification involved in this use case?
2. Is this classification permitted in the proposed AI platform under existing organisational policy?
3. Have applicable DLP, information-security, privacy and acceptable-use requirements been checked?
4. If classification or permitted use is unclear, has IT / Information Security / Privacy / Risk been consulted?
5. Is the source, ownership and permitted use of input data understood?
6. Could prompts, uploaded information or outputs be retained or used by the provider for training or service improvement?
7. Are data location, retention and deletion arrangements understood and acceptable?
8. Could generated outputs expose confidential information, intellectual property or copyrighted material?
9. Could source code, configuration, credentials, secrets, tokens or connection information be exposed through the use case?

**Escalation trigger:** Sensitive or regulated data, unclear classification, unclear ownership, unclear provider retention/training terms, unresolved intellectual-property concerns, or possible exposure of credentials/secrets should trigger further review before operational use.

## 3. Platform and supplier

1. Is the AI platform approved for organisational use?
2. Has the supplier/platform been assessed for security, privacy and contractual risk at a level proportionate to the use case?
3. Are authentication, access control and administrative ownership appropriate?
4. Can usage be logged, monitored and reviewed?
5. Is there an acceptable exit path if the service changes, fails or is withdrawn?
6. Are material subcontractors, integrations or external data flows understood?

## 4. Impact and decision risk

**Data sensitivity and AI use-case impact are related but different.** Public data can still support a high-impact AI decision; confidential data may sometimes be used safely in an approved enterprise platform with appropriate controls.

1. Could an incorrect, biased or misleading output cause material harm to a person, customer, organisation or community?
2. Will AI materially influence a decision affecting an individual, such as employment, credit, eligibility, health, safety or access to a service?
3. Will people interact directly with AI, or receive AI-generated outputs, without meaningful human review?
4. Could failure or unavailability materially disrupt a critical business process?
5. Is there a realistic risk of discriminatory, unfair or systematically biased outcomes?
6. Is the use case operating in a regulated, safety-critical or otherwise high-consequence environment?

**Escalation trigger:** A "Yes" to a high-impact decision, material-harm, safety-critical or regulated-use question should normally require fuller assessment and appropriate specialist review.

## 5. Human oversight and quality

1. Is a named person or role accountable for the use case?
2. Is human review required before material outputs or decisions are acted upon?
3. Do reviewers understand that AI outputs can be inaccurate, incomplete or fabricated?
4. Is there a practical method to validate important outputs against authoritative information?
5. Can a person challenge, override or correct an AI-supported outcome where appropriate?
6. Are users trained on acceptable use, limitations, data handling and escalation?

## 6. Security and misuse

1. Have plausible misuse scenarios been considered?
2. Could the use case enable fraud, impersonation, unsafe automation, data leakage or unauthorised actions?
3. Are permissions limited to what the AI actually needs?
4. If the AI can invoke tools, code, workflows or other systems, are consequential actions appropriately constrained and reviewed?
5. Are incident reporting and response paths clear?
6. Is monitoring proportionate to the potential impact?

## 7. Transparency, lifecycle and review

1. Is it clear when and how AI is being used in the process?
2. Where appropriate, will affected people know that AI contributed to an interaction, recommendation or decision?
3. Are key assumptions, limitations, controls and approvals documented?
4. Is there an owner for ongoing monitoring?
5. Are measurable performance/quality indicators defined?
6. Will the assessment be revisited after material changes to model, platform, data, purpose, users, integrations or risk?

## 8. Decision

Choose one:

- **PROCEED** - Low-risk use case; existing controls are adequate.
- **PROCEED WITH CONTROLS** - Use is acceptable once listed controls are implemented and owned.
- **FURTHER ASSESSMENT REQUIRED** - Material uncertainty or elevated impact requires specialist/privacy/security/legal/risk assessment before approval.
- **DO NOT PROCEED** - Risk cannot currently be reduced to an acceptable level or the proposed use conflicts with organisational requirements.

### Required controls / actions

| Action / control | Owner | Due | Status |
|---|---|---|---|
| | | | |
| | | | |
| | | | |

Decision:  
Approver:  
Date:  
Next review / trigger:

## Practical principle

The objective is not to make every AI use case risk-free. It is to make the decision **deliberate, proportionate, documented and owned**.

## Reference alignment

This independent practical tool is informed by, but is not a reproduction of, the Australian Government Digital Transformation Agency AI impact-assessment approach and the NIST AI Risk Management Framework / Generative AI Profile.

Organisations should apply their own legal, regulatory, privacy, security, procurement, data-classification, DLP and risk-management requirements.

## Changelog

### v0.2 - August 2026
- Added explicit alignment to organisational data classification.
- Added DLP and local IT / Information Security / Privacy / Risk escalation.
- Added illustrative data-handling model.
- Distinguished data sensitivity from AI use-case impact.
- Added source-code, credential, secret and configuration exposure considerations.
- Updated core assessment model.

### v0.1 - August 2026
- Initial complete assessment framework.
