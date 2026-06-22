# EU AI Act Mapping

## Purpose

This document maps the governance controls implemented for the EthosSutra Enterprise Copilot to applicable requirements of the European Union Artificial Intelligence Act (EU AI Act).

The objective is to demonstrate how governance controls, operational processes and documentation support responsible AI practices and regulatory preparedness.

This assessment applies a risk-based approach consistent with the structure and intent of the EU AI Act.

## AI System Overview

| Field                      | Value                                      |
| -------------------------- | ------------------------------------------ |
| AI System                  | EthosSutra Enterprise Copilot              |
| AI Type                    | Retrieval-Augmented Generation (RAG)       |
| Foundation Model           | GPT-5                                      |
| Primary Purpose            | Governance, Risk and Compliance Assistance |
| Decision Authority         | Human Controlled                           |
| Autonomous Decision Making | No                                         |
| Human Oversight Required   | Yes                                        |

## EU AI Act Risk Classification Assessment

The EU AI Act applies a risk-based framework to AI systems.

### Prohibited Risk

Examples include:

* Social scoring
* Manipulative AI systems
* Exploitative AI systems

Assessment:

Not Applicable

### High-Risk AI Systems

Examples include:

* Employment screening systems
* Credit scoring systems
* Educational assessment systems
* Critical infrastructure systems
* Law enforcement systems

Assessment:

Not Applicable

The EthosSutra Enterprise Copilot does not make decisions regarding employment, credit, healthcare, education or other regulated high-risk activities.

### Limited Risk AI Systems

Examples include:

* Conversational AI
* AI assistants
* Enterprise copilots
* Information support systems

Assessment:

Applicable

The EthosSutra Enterprise Copilot operates as an enterprise knowledge and governance assistant supporting human decision-making.

### Minimal Risk AI Systems

Assessment:

Partially Applicable

Certain informational use cases may fall within minimal-risk categories.

### Final Classification

| Classification  | Status  |
| --------------- | ------- |
| Prohibited Risk | No      |
| High-Risk       | No      |
| Limited Risk    | Yes     |
| Minimal Risk    | Partial |

## Transparency Obligations

### Requirement

Users should be informed when interacting with an AI system.

### Implementation

The system is identified as an AI-assisted governance support solution.

Users are informed that outputs are AI-generated and subject to human review.

### Evidence

* Use_Case_Description.md
* AI_Governance_Policy.md
* Human_Oversight_Plan.md

### Audit Validation

Review user-facing disclosures and governance documentation.

## Human Oversight Requirements

### Requirement

Appropriate human oversight should be maintained.

### Implementation

Human review and approval requirements are documented.

The system does not make autonomous governance decisions.

Final accountability remains with designated stakeholders.

### Evidence

* Human_Oversight_Plan.md
* RACI_Matrix.md
* Monitoring_Log.md

### Audit Validation

Review oversight procedures and governance approval activities.

## Accuracy and Reliability

### Requirement

AI systems should operate reliably within intended use.

### Implementation

Testing and validation activities assess:

* Response quality
* Hallucination risk
* Retrieval effectiveness
* Governance consistency

### Evidence

* Testing_Strategy.md
* Hallucination_Testing.md
* Validation_Report.md

### Audit Validation

Review testing records and validation results.

## Risk Management

### Requirement

AI-related risks should be identified and managed.

### Implementation

The governance framework includes:

* Risk assessments
* Risk registers
* Control libraries
* Continuous monitoring

### Evidence

* AI_Risk_Assessment.md
* Risk_Register.md
* AI_Control_Library.md

### Audit Validation

Review risk identification and mitigation activities.

## Technical Documentation

### Requirement

Appropriate technical documentation should be maintained.

### Implementation

Comprehensive system documentation exists covering:

* Architecture
* Model information
* Governance controls
* Operational processes

### Evidence

* Technical_Architecture.md
* Model_Card.md
* System_Description.md

### Audit Validation

Review completeness of technical documentation.

## Record Keeping

### Requirement

Appropriate records should support accountability and oversight.

### Implementation

Governance records are maintained through:

* Monitoring logs
* Incident records
* Risk registers
* Validation reports

### Evidence

* Monitoring_Log.md
* Incident_Register.md
* Validation_Report.md

### Audit Validation

Review governance evidence and record retention activities.

## Monitoring and Post-Deployment Activities

### Requirement

AI systems should be monitored throughout operation.

### Implementation

Continuous monitoring activities assess:

* Performance
* Hallucination trends
* Governance effectiveness
* Incident trends

### Evidence

* Monitoring_Plan.md
* KPI_Definitions.md
* Monitoring_Log.md

### Audit Validation

Review monitoring activities and management reporting.

## Incident Management

### Requirement

Organizations should manage significant AI-related incidents.

### Implementation

Incident response procedures support:

* Detection
* Escalation
* Investigation
* Remediation
* Lessons learned

### Evidence

* Incident_Response_Plan.md
* Incident_Register.md

### Audit Validation

Review incident records and corrective actions.

## Third-Party Provider Governance

### Requirement

Organizations should understand and manage third-party dependencies.

### Implementation

Vendor risks are assessed and monitored through formal governance processes.

### Evidence

* Vendor_Risk_Assessment.md
* Monitoring_Plan.md

### Audit Validation

Review vendor assessment records and monitoring activities.

## General Purpose AI Considerations

The EthosSutra Enterprise Copilot relies upon a General Purpose AI (GPAI) model provided by OpenAI.

The organization does not develop or modify the foundation model.

Responsibilities therefore focus on:

* Safe deployment
* Appropriate oversight
* Risk management
* Monitoring
* Governance controls

Model provider obligations remain with the foundation model provider.

## Compliance Readiness Assessment

| Area                    | Status      |
| ----------------------- | ----------- |
| Transparency            | Implemented |
| Human Oversight         | Implemented |
| Risk Management         | Implemented |
| Technical Documentation | Implemented |
| Monitoring              | Implemented |
| Incident Management     | Implemented |
| Vendor Governance       | Implemented |

## Key Governance Strengths

The EthosSutra Enterprise Copilot demonstrates:

* Risk-based governance
* Human-in-the-loop decision making
* Structured risk management
* Technical transparency
* Continuous monitoring
* Incident response capabilities
* Vendor governance controls

## Regulatory Considerations

If future functionality expands into:

* Employee evaluation
* Candidate screening
* Credit assessment
* Healthcare decision support
* Educational assessment

the AI system classification should be reassessed to determine whether High-Risk AI obligations become applicable.

## Conclusion

Based on the current use case, architecture and operating model, the EthosSutra Enterprise Copilot is classified as a Limited Risk AI System under the EU AI Act.

The implemented governance framework provides controls supporting transparency, accountability, human oversight, monitoring and responsible AI operation.

## Related Documents

* AI_Governance_Policy.md
* Human_Oversight_Plan.md
* AI_Risk_Assessment.md
* Monitoring_Plan.md
* Vendor_Risk_Assessment.md
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
