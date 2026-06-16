# Model Card

## Purpose

This Model Card provides a standardized description of the AI model and supporting technologies used within the EthosSutra Enterprise Copilot.

The document supports transparency, accountability, risk management and governance oversight by documenting model capabilities, limitations, intended uses and associated governance controls.

## Model Identification

| Field                     | Value                                |
| ------------------------- | ------------------------------------ |
| AI System Name            | EthosSutra Enterprise Copilot        |
| AI System ID              | ES-AI-001                            |
| Model Type                | Large Language Model (LLM)           |
| Foundation Model Provider | OpenAI                               |
| Foundation Model          | GPT-5                                |
| Deployment Pattern        | Retrieval-Augmented Generation (RAG) |
| Model Access Method       | API                                  |
| Fine-Tuned Model          | No                                   |
| Status                    | Active                               |

## Model Purpose

The EthosSutra Enterprise Copilot is designed to assist governance, risk and compliance professionals by providing contextual guidance based on approved governance documentation.

The system is intended to support:

* AI Governance
* AI Risk Management
* Compliance Activities
* Internal Audit Preparation
* Governance Documentation
* Governance Training and Awareness

The system is designed to augment human decision-making and not replace human judgment.

## Intended Users

The system is intended for:

* AI Governance Professionals
* AI Risk Managers
* Compliance Specialists
* Internal Auditors
* Responsible AI Practitioners
* Governance Analysts
* Students and Learners

## Out-of-Scope Use Cases

The system must not be used as the sole basis for:

* Legal advice
* Regulatory approvals
* Compliance certification
* Risk acceptance decisions
* Employment decisions
* Financial decisions
* Medical decisions

Human review remains mandatory.

## Technical Architecture

| Component           | Technology                     |
| ------------------- | ------------------------------ |
| Foundation Model    | GPT-5                          |
| Embedding Model     | text-embedding-3-large         |
| Retrieval Pattern   | Retrieval-Augmented Generation |
| Vector Database     | ChromaDB                       |
| Backend Framework   | FastAPI                        |
| Frontend Framework  | Next.js                        |
| User Interface      | React                          |
| Cloud Platform      | Microsoft Azure                |
| Identity Management | Microsoft Entra ID             |

## Input Data

The model receives:

* User prompts
* Governance documentation
* Policy documents
* Risk assessments
* Framework mappings
* Human oversight documentation
* Audit evidence documentation

Only approved knowledge sources may be included within the retrieval layer.

## Output Types

The model may generate:

* Governance recommendations
* Risk management guidance
* Compliance explanations
* Documentation summaries
* Framework interpretations
* Audit preparation support

Outputs are advisory in nature.

## Model Capabilities

The system is capable of:

* Natural language understanding
* Context-aware responses
* Governance knowledge retrieval
* Policy interpretation support
* Risk management assistance
* Documentation support

## Known Limitations

The model may:

* Generate inaccurate responses
* Misinterpret ambiguous prompts
* Produce incomplete recommendations
* Reference outdated information if knowledge sources are not maintained
* Exhibit limitations associated with foundation model behavior

Users must validate outputs before use.

## Risk Considerations

| Risk Area              | Assessment |
| ---------------------- | ---------- |
| Hallucination Risk     | Medium     |
| Prompt Injection Risk  | Medium     |
| Data Leakage Risk      | Medium     |
| Vendor Dependency Risk | Medium     |
| Compliance Risk        | Medium     |
| Operational Risk       | Medium     |

Associated controls are documented within the AI Risk Assessment and Risk Register.

## Human Oversight Controls

Human review is required for:

* Governance recommendations
* Compliance interpretations
* Risk assessments
* Audit conclusions
* Control implementation decisions

Final accountability remains with designated human stakeholders.

## Monitoring Requirements

The following activities require monitoring:

* Response quality
* User feedback
* Security events
* Knowledge base quality
* Vendor performance
* Incident trends

Monitoring activities are documented within the Monitoring Plan.

## Third-Party Dependencies

| Vendor          | Service                    |
| --------------- | -------------------------- |
| OpenAI          | Foundation Model Services  |
| Microsoft Azure | Cloud Infrastructure       |
| GitHub          | Source Code Management     |
| ChromaDB        | Vector Database Technology |

Third-party vendors are subject to vendor risk assessment processes.

## Governance Controls

The model is governed through:

* AI Governance Policy
* AI Risk Assessment
* Human Oversight Plan
* Testing Strategy
* Monitoring Plan
* Vendor Risk Assessment
* Incident Response Plan

## Regulatory Alignment

This model supports governance activities aligned to:

* NIST AI RMF
* ISO/IEC 42001
* EU AI Act
* Responsible AI Principles

## Review Requirements

This Model Card should be reviewed following:

* Major model updates
* Architecture changes
* Vendor changes
* Significant incidents
* Regulatory changes

## Document Ownership

| Field            | Value              |
| ---------------- | ------------------ |
| Document Owner   | AI Governance Lead |
| Review Frequency | Annual             |
| Classification   | Internal           |
| Status           | Active             |

**Version:** 1.0

**Last Updated:** June 2026
