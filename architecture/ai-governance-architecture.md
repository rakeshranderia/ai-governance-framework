# AI Governance Architecture

## Overview

AI governance should operate across the full technology and business environment.

The architecture below illustrates how users, business applications, AI services, data, security and governance capabilities can be connected within an enterprise environment.

---

## High-Level Architecture

```mermaid
flowchart TB

    Users[Employees & Customers]

    Business[Business Applications<br/>CRM / ERP / Workflow / Portals]

    AI[AI Services<br/>Copilot / LLM / AI Applications]

    Data[Enterprise Data<br/>Documents / Databases / Knowledge]

    Identity[Identity & Access<br/>SSO / MFA / RBAC]

    Security[Security Controls<br/>DLP / EDR / Monitoring]

    Governance[AI Governance<br/>Policy / Risk / Approval]

    Monitoring[AI Monitoring<br/>Usage / Performance / Risk]

    ThirdParty[AI Providers<br/>Cloud / SaaS / Model Providers]

    Users --> Business
    Users --> AI

    Business --> AI
    AI --> Data
    AI --> ThirdParty

    Identity --> Users
    Identity --> Business
    Identity --> AI

    Security --> Business
    Security --> AI
    Security --> Data

    Governance --> AI
    Governance --> ThirdParty

    AI --> Monitoring
    Monitoring --> Governance
