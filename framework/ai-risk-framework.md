# AI Risk Framework

## Overview

AI risk should be assessed according to the specific use case, the information involved, the people affected and the potential business impact.

A risk-based approach allows organisations to encourage low-risk experimentation while applying stronger governance to higher-risk applications.

---

## AI Risk Assessment Model

A practical assessment can be structured across six dimensions:

1. Business Impact
2. Data Sensitivity
3. Decision Impact
4. Security Risk
5. Regulatory and Legal Risk
6. Third-Party Dependency

Each dimension should be considered when determining the overall risk tier.

---

## 1. Business Impact

Consider the potential impact if the AI system produces an incorrect, unavailable or inappropriate result.

### Low

Limited impact on business operations.

### Medium

Could disrupt a business process or require manual intervention.

### High

Could materially affect customers, employees or critical operations.

### Critical

Could result in significant financial, regulatory, safety or reputational consequences.

---

## 2. Data Sensitivity

Consider the information processed by the AI system.

| Level | Example |
|---|---|
| **Low** | Public information |
| **Medium** | Internal business information |
| **High** | Confidential or commercially sensitive information |
| **Critical** | Highly sensitive personal, financial or regulated information |

---

## 3. Decision Impact

Consider whether AI is simply assisting a person or influencing a material decision.

### Low

AI assists with productivity or administrative tasks.

### Medium

AI provides recommendations that are reviewed by a person.

### High

AI materially influences decisions affecting customers or employees.

### Critical

AI makes or substantially determines a material decision without meaningful human oversight.

---

## 4. Security Risk

Consider:

- Data leakage
- Unauthorised access
- Prompt injection
- Model manipulation
- Malicious inputs
- Insecure integrations
- Model or service compromise
- Availability

---

## 5. Regulatory and Legal Risk

Consider:

- Privacy obligations
- Financial services obligations
- Employment requirements
- Consumer protection
- Intellectual property
- Contractual obligations
- Industry regulation
- Emerging AI regulation

---

## 6. Third-Party Dependency

Consider:

- AI model provider
- Cloud provider
- Data processor
- Subprocessors
- Service availability
- Data residency
- Contractual protections
- Exit strategy

---

## Risk Tiering

The assessment should produce an overall risk tier.

| Tier | Typical Use Case | Governance |
|---|---|---|
| **Low** | Productivity assistance | Acceptable-use controls |
| **Medium** | Internal decision support | Risk assessment |
| **High** | Customer or employee impact | Formal approval + monitoring |
| **Critical** | Material automated decisions | Enhanced governance + executive oversight |

---

## Control Selection

Controls should be proportional to the risk.

Potential controls include:

- Access controls
- Data minimisation
- Encryption
- Human review
- Output validation
- Logging
- Monitoring
- Model testing
- Security testing
- Privacy assessment
- Supplier assurance
- Incident response
- Business continuity

---

## AI Use Case Decision

Following assessment, an AI use case may be:

**Approved**

The identified risks are acceptable with existing controls.

**Approved with Conditions**

The use case may proceed provided specified controls are implemented.

**Requires Further Assessment**

Additional information or specialist assessment is required.

**Restricted**

The use case may only operate within defined limitations.

**Not Approved**

The residual risk exceeds the organisation's risk appetite.

---

## Example Assessment

### Use Case

Internal AI assistant used to summarise non-sensitive business documents.

### Assessment

| Dimension | Assessment |
|---|---|
| Business Impact | Low |
| Data Sensitivity | Low / Medium |
| Decision Impact | Low |
| Security Risk | Medium |
| Regulatory Risk | Low |
| Third-Party Dependency | Medium |

### Overall Risk

**Low / Medium**

### Controls

- Approved enterprise AI platform
- User authentication
- Data handling requirements
- Acceptable-use policy
- Human review
- Usage monitoring

### Decision

**Approved with standard controls**

---

## Executive Perspective

Risk-based AI governance allows organisations to avoid two extremes:

**Uncontrolled AI adoption**

and

**Governance that prevents useful innovation.**

The objective is to match the level of governance to the potential impact of the AI use case.

> **Higher potential impact = stronger governance and assurance.**