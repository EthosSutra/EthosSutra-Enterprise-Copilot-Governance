# NIST AI RMF Mapping

## Purpose

This document maps the governance controls implemented for the EthosSutra Enterprise Copilot to the NIST AI Risk Management Framework (AI RMF) 1.0.

The objective is to demonstrate how governance activities, controls and evidence support responsible AI practices across the AI system lifecycle.

This mapping supports governance assurance, audit readiness and alignment with recognized industry standards.

## NIST AI RMF Overview

The NIST AI Risk Management Framework is structured around four core functions:

| Function      | Purpose                                                       |
| ------------- | ------------------------------------------------------------- |
| Govern (GOV)  | Establish governance structures, accountability and oversight |
| Map (MAP)     | Understand context, risks and intended use                    |
| Measure (MEA) | Assess, test and evaluate AI risks                            |
| Manage (MAN)  | Respond to and manage identified risks                        |

The EthosSutra Enterprise Copilot governance program incorporates controls across all four functions.

## AI System Context

| Field                    | Value                                      |
| ------------------------ | ------------------------------------------ |
| AI System                | EthosSutra Enterprise Copilot              |
| AI Type                  | Retrieval-Augmented Generation (RAG)       |
| Primary Purpose          | Governance, Risk and Compliance Assistance |
| Foundation Model         | GPT-5                                      |
| Risk Classification      | Moderate                                   |
| Human Oversight Required | Yes                                        |

## GOVERN Function Mapping

### GOV 1.1 – Organizational AI Governance Structure

**Requirement**

Governance structures and accountability mechanisms are established.

**Implementation**

The project defines governance ownership, review responsibilities and accountability through documented governance artefacts.

**Evidence**

* Stakeholder_Map.md
* AI_Governance_Policy.md
* RACI_Matrix.md

**Audit Validation**

Verify governance ownership and approval responsibilities are documented.

---

### GOV 2.1 – Roles and Responsibilities

**Requirement**

Roles related to AI governance are assigned and maintained.

**Implementation**

Governance, technical, compliance and oversight responsibilities are formally defined.

**Evidence**

* Stakeholder_Map.md
* Human_Oversight_Plan.md
* RACI_Matrix.md

**Audit Validation**

Review role assignments and governance accountability records.

---

### GOV 3.2 – Human Oversight

**Requirement**

Appropriate human oversight mechanisms are established.

**Implementation**

Human review requirements and escalation processes are documented.

**Evidence**

* Human_Oversight_Plan.md
* Monitoring_Log.md
* Incident_Register.md

**Audit Validation**

Review evidence of oversight activities and approval processes.

---

### GOV 6.1 – Policies and Procedures

**Requirement**

AI governance policies are documented and maintained.

**Implementation**

Governance policies support responsible AI operation and risk management.

**Evidence**

* AI_Governance_Policy.md
* Acceptable_Use_Policy.md
* Data_Handling_Guidelines.md

**Audit Validation**

Verify policy approval, maintenance and review activities.

## MAP Function Mapping

### MAP 1.1 – Intended Purpose and Context

**Requirement**

The intended purpose and operating context are understood.

**Implementation**

The use case, business objectives and stakeholder impacts are documented.

**Evidence**

* Use_Case_Description.md
* Business_Context.md
* Stakeholder_Map.md

**Audit Validation**

Review use case documentation and stakeholder analysis.

---

### MAP 2.1 – Risk Identification

**Requirement**

Potential AI risks are identified and documented.

**Implementation**

Risk assessments identify governance, compliance, operational and technical risks.

**Evidence**

* AI_Risk_Assessment.md
* Risk_Register.md

**Audit Validation**

Review risk identification methodology and documented risks.

---

### MAP 3.1 – Third-Party Dependencies

**Requirement**

Dependencies on external vendors and technologies are assessed.

**Implementation**

Critical vendors and supporting services are evaluated through formal assessments.

**Evidence**

* Vendor_Risk_Assessment.md
* Technical_Architecture.md

**Audit Validation**

Verify vendor risk reviews and dependency analysis.

## MEASURE Function Mapping

### MEA 1.1 – Risk Evaluation

**Requirement**

AI risks are assessed using documented methodologies.

**Implementation**

Risk assessments evaluate likelihood, impact and residual risk.

**Evidence**

* AI_Risk_Assessment.md
* Risk_Register.md

**Audit Validation**

Review risk scoring and mitigation activities.

---

### MEA 2.1 – Testing and Validation

**Requirement**

AI systems are tested before deployment.

**Implementation**

Formal testing and validation processes assess functionality, governance controls and response quality.

**Evidence**

* Testing_Strategy.md
* Validation_Report.md

**Audit Validation**

Review testing records and approval decisions.

---

### MEA 3.1 – Response Quality Assessment

**Requirement**

Output quality is evaluated and monitored.

**Implementation**

Response quality and retrieval effectiveness are measured through testing and monitoring activities.

**Evidence**

* Monitoring_Plan.md
* KPI_Definitions.md
* Monitoring_Log.md

**Audit Validation**

Review monitoring metrics and performance reports.

---

### MEA 4.1 – Hallucination Assessment

**Requirement**

Potential inaccuracies and unsupported outputs are evaluated.

**Implementation**

Hallucination testing methodology and acceptance criteria are formally defined.

**Evidence**

* Hallucination_Testing.md
* Validation_Report.md

**Audit Validation**

Review hallucination testing results and remediation activities.

## MANAGE Function Mapping

### MAN 1.1 – Risk Treatment

**Requirement**

Identified risks are managed through controls and mitigation activities.

**Implementation**

Risks are linked to documented governance controls.

**Evidence**

* AI_Control_Library.md
* Risk_Register.md

**Audit Validation**

Review control implementation and risk treatment plans.

---

### MAN 2.1 – Continuous Monitoring

**Requirement**

AI risks and controls are monitored throughout operation.

**Implementation**

Monitoring activities track performance, governance effectiveness and emerging risks.

**Evidence**

* Monitoring_Plan.md
* KPI_Definitions.md
* Monitoring_Log.md

**Audit Validation**

Review monitoring records and governance reviews.

---

### MAN 3.1 – Incident Management

**Requirement**

Processes exist for identifying and responding to AI incidents.

**Implementation**

Incident response procedures define escalation, investigation and remediation requirements.

**Evidence**

* Incident_Response_Plan.md
* Incident_Register.md

**Audit Validation**

Review incident records and corrective actions.

---

### MAN 4.1 – Continuous Improvement

**Requirement**

Governance controls and processes are improved over time.

**Implementation**

Lessons learned, monitoring results and incident reviews drive governance enhancements.

**Evidence**

* Monitoring_Log.md
* Incident_Register.md
* Validation_Report.md

**Audit Validation**

Review documented improvements and governance updates.

## Coverage Summary

| NIST Function | Coverage Status |
| ------------- | --------------- |
| Govern        | Implemented     |
| Map           | Implemented     |
| Measure       | Implemented     |
| Manage        | Implemented     |

## Key Governance Strengths

The EthosSutra Enterprise Copilot governance framework demonstrates:

* Defined governance ownership
* Formal risk management processes
* Human oversight mechanisms
* Testing and validation controls
* Continuous monitoring activities
* Incident management procedures
* Vendor risk management controls
* Audit-ready documentation

## Identified Improvement Opportunities

Future enhancements may include:

* Automated governance dashboards
* Expanded model performance analytics
* Advanced adversarial testing
* Independent governance reviews
* Enhanced vendor monitoring capabilities

## Related Documents

* AI_Control_Library.md
* AI_Risk_Assessment.md
* Human_Oversight_Plan.md
* Validation_Report.md
* Monitoring_Plan.md
* Incident_Response_Plan.md

## Document Ownership

| Field            | Value              |
| ---------------- | ------------------ |
| Document Owner   | AI Governance Lead |
| Review Frequency | Annual             |
| Classification   | Internal           |
| Status           | Active             |

**Version:** 1.0

**Last Updated:** June 2026
