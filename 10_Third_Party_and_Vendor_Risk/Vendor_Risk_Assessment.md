# Vendor Risk Assessment

## Purpose

This document records the risk assessment performed for third-party vendors supporting the EthosSutra Enterprise Copilot.

The objective is to evaluate vendor-related risks and determine whether appropriate controls exist to support secure, compliant and reliable operation of the AI system.

This assessment follows a risk-based approach aligned with enterprise governance, security and compliance practices.

## Assessment Information

| Field             | Value                     |
| ----------------- | ------------------------- |
| Assessment ID     | VRA-001                   |
| Assessment Type   | AI Vendor Risk Assessment |
| Assessment Date   | June 2026                 |
| Assessment Owner  | AI Governance Lead        |
| Assessment Status | Approved with Monitoring  |

## Vendor Profile

### Vendor Name

OpenAI

### Vendor Type

AI Foundation Model Provider

### Service Provided

Large Language Model Services

### Criticality Rating

High

### Business Dependency

High

### Assessment Scope

The assessment covers:

* AI services
* Data handling practices
* Security controls
* Privacy controls
* Operational resilience
* Compliance posture
* AI governance practices
* Vendor dependency risks

## Vendor Architecture Role

| Vendor          | Service                   |
| --------------- | ------------------------- |
| OpenAI          | Foundation Model Provider |
| Microsoft Azure | Cloud Infrastructure      |
| GitHub          | Source Code Management    |
| ChromaDB        | Vector Database Platform  |

OpenAI is considered a critical vendor due to its role in AI response generation.

## Inherent Risk Assessment

| Risk Domain            | Rating |
| ---------------------- | ------ |
| Information Security   | High   |
| Privacy Risk           | High   |
| Regulatory Risk        | Medium |
| Operational Risk       | High   |
| Vendor Dependency Risk | High   |
| AI Model Risk          | High   |
| Availability Risk      | Medium |
| Reputational Risk      | Medium |

### Overall Inherent Risk

High

## Security Assessment

### Assessment Areas

* Access Controls
* Authentication Controls
* Encryption Practices
* Security Monitoring
* Incident Management
* Vulnerability Management

### Assessment Outcome

No material security concerns identified based on publicly available information and contractual controls.

### Risk Rating

Medium

## Privacy and Data Protection Assessment

### Assessment Areas

* Data Processing Activities
* Data Retention Practices
* Privacy Controls
* Cross-Border Data Transfers
* User Data Protection

### Key Considerations

* Data submitted to AI services may contain sensitive information.
* Appropriate data handling controls are required.
* Sensitive or regulated data should not be submitted without approved controls.

### Risk Rating

Medium

## AI Governance Assessment

### Assessment Areas

* Responsible AI Practices
* Model Transparency
* Safety Controls
* Risk Management Processes
* Model Monitoring Practices

### Assessment Outcome

Vendor demonstrates established AI governance practices and publishes information regarding model safety and responsible AI development.

### Risk Rating

Medium

## Operational Resilience Assessment

### Assessment Areas

* Service Availability
* Disaster Recovery
* Business Continuity
* Incident Response

### Key Risks

* Dependence on external AI services
* Vendor service outages
* API availability disruptions

### Risk Rating

Medium

## Compliance Assessment

### Assessment Areas

* Regulatory Alignment
* Data Protection Requirements
* Contractual Obligations
* Audit Support

### Assessment Outcome

Compliance obligations should be supported through contractual controls, internal governance controls and ongoing monitoring.

### Risk Rating

Medium

## Concentration Risk Assessment

### Assessment Description

The EthosSutra Enterprise Copilot currently depends on a single foundation model provider.

### Key Risks

* Vendor lock-in
* Service disruption
* Pricing changes
* Technology dependency

### Risk Rating

High

### Mitigation Actions

* Monitor vendor performance
* Maintain architecture documentation
* Evaluate alternative providers periodically
* Maintain contingency procedures

## Subprocessor Assessment

The organization should review vendor disclosures regarding subprocessors and supporting service providers.

Areas of consideration include:

* Data hosting providers
* Infrastructure providers
* Security service providers
* Support service providers

### Risk Rating

Medium

## Residual Risk Assessment

| Risk Domain            | Residual Risk |
| ---------------------- | ------------- |
| Information Security   | Medium        |
| Privacy Risk           | Medium        |
| Regulatory Risk        | Low           |
| Operational Risk       | Medium        |
| Vendor Dependency Risk | Medium        |
| AI Model Risk          | Medium        |
| Availability Risk      | Medium        |

### Overall Residual Risk

Medium

## Required Controls

The following controls should remain in place:

* Human oversight controls
* Data handling controls
* Vendor monitoring procedures
* Incident management procedures
* Security monitoring activities
* Periodic vendor reassessments

## Monitoring Requirements

The following activities should occur after vendor approval:

| Activity                  | Frequency   |
| ------------------------- | ----------- |
| Vendor Performance Review | Quarterly   |
| Security Review           | Annual      |
| Compliance Review         | Annual      |
| Incident Review           | As Required |
| Contract Review           | Annual      |

## Assessment Decision

### Approval Status

Approved with Monitoring

### Rationale

The vendor provides critical AI capabilities required for operation of the EthosSutra Enterprise Copilot.

Identified risks are considered manageable through governance controls, monitoring activities and human oversight mechanisms.

## Approval Record

| Role               | Status   |
| ------------------ | -------- |
| AI Governance Lead | Approved |
| System Owner       | Approved |
| Technical Owner    | Approved |

## Related Documents

* AI_Risk_Assessment.md
* Monitoring_Plan.md
* Incident_Response_Plan.md
* Human_Oversight_Plan.md
* AI_Inventory_Register.md

## Document Ownership

| Field            | Value              |
| ---------------- | ------------------ |
| Document Owner   | AI Governance Lead |
| Review Frequency | Annual             |
| Classification   | Internal           |
| Status           | Active             |

**Version:** 1.0

**Last Updated:** June 2026
