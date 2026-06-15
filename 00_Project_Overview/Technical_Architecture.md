# Technical Architecture

## Purpose

This document provides a high-level technical architecture overview of the EthosSutra Enterprise Copilot.

The objective is to establish a common understanding of the system components, technology stack, data flows and third-party dependencies that support governance, risk management, compliance and audit activities.

This document serves as a foundational reference for:

* AI System Inventory
* Risk Assessment
* Vendor Risk Assessment
* Human Oversight Planning
* Control Design
* Monitoring Activities
* Incident Management
* Audit Evidence Collection

---

# System Overview

EthosSutra Enterprise Copilot is a Retrieval-Augmented Generation (RAG) based enterprise AI assistant designed to support users with AI governance, compliance, risk management and responsible AI guidance.

The system combines Large Language Model (LLM) capabilities with a curated knowledge repository to generate contextual responses grounded in approved governance content.

---

# Architecture Principles

The architecture is designed to support:

* Responsible AI practices
* Human oversight
* Traceability
* Explainability
* Auditability
* Security
* Scalability
* Governance by design

---

# High-Level Architecture

```text
┌─────────────────────────────┐
│        End Users            │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│       Web Application       │
│          Next.js            │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│       FastAPI Backend       │
└──────────────┬──────────────┘
               │
       ┌───────┴────────┐
       ▼                ▼
┌──────────────┐  ┌──────────────┐
│ OpenAI GPT   │  │ ChromaDB     │
│ Foundation   │  │ Vector Store │
│ Model        │  └──────────────┘
└──────────────┘          │
                          ▼
                 ┌────────────────┐
                 │ Knowledge Base │
                 │ Policies       │
                 │ Frameworks     │
                 │ Governance Docs│
                 └────────────────┘

               ▼
┌─────────────────────────────┐
│ Monitoring & Logging Layer  │
└─────────────────────────────┘
```

---

# Technology Stack

## User Interface

| Component            | Technology |
| -------------------- | ---------- |
| Frontend Application | Next.js    |
| User Interface       | React      |
| Browser Access       | Web Based  |

---

## Application Layer

| Component          | Technology             |
| ------------------ | ---------------------- |
| API Layer          | FastAPI                |
| Business Logic     | Python                 |
| Prompt Management  | Application Controlled |
| Session Management | Backend Services       |

---

## AI Layer

| Component            | Technology           |
| -------------------- | -------------------- |
| Foundation Model     | OpenAI GPT           |
| AI Capability        | Generative AI        |
| Response Generation  | Large Language Model |
| Embedding Generation | OpenAI Embeddings    |

---

## Knowledge Layer

| Component            | Technology             |
| -------------------- | ---------------------- |
| Retrieval Pattern    | RAG                    |
| Vector Database      | ChromaDB               |
| Knowledge Repository | Governance Artefacts   |
| Source Documents     | Markdown Documentation |

---

## Infrastructure Layer

| Component        | Technology         |
| ---------------- | ------------------ |
| Hosting Platform | Microsoft Azure    |
| Source Control   | GitHub             |
| Authentication   | Microsoft Entra ID |
| Monitoring       | Azure Monitor      |
| Logging          | Application Logs   |

---

# Knowledge Sources

The EthosSutra Enterprise Copilot retrieves information from approved governance documentation including:

* Governance Policies
* Risk Assessments
* AI Inventory Records
* Human Oversight Plans
* Control Libraries
* Framework Mappings
* Audit Evidence Documentation
* Governance Procedures

Only approved knowledge sources may be used to generate responses.

---

# Data Flow

## Step 1

User submits a governance-related query.

## Step 2

The application processes the request and performs retrieval against the vector database.

## Step 3

Relevant governance content is retrieved from approved knowledge sources.

## Step 4

Retrieved content is provided to the foundation model as contextual information.

## Step 5

The model generates a response using retrieved context.

## Step 6

The response is returned to the user.

## Step 7

Monitoring and logging records are generated for governance purposes.

---

# Third-Party Dependencies

| Vendor          | Service                    |
| --------------- | -------------------------- |
| OpenAI          | Foundation Model Services  |
| Microsoft Azure | Cloud Infrastructure       |
| GitHub          | Source Code Management     |
| ChromaDB        | Vector Database Technology |

These dependencies are subject to third-party risk assessment and ongoing monitoring activities.

---

# Governance Considerations

The architecture introduces several governance considerations:

* Hallucination Risk
* Prompt Injection Risk
* Data Leakage Risk
* Vendor Dependency Risk
* Model Performance Risk
* Knowledge Base Accuracy Risk
* Access Control Risk

These risks are assessed through the AI Governance Framework.

---

# Human Oversight

Human oversight is required for:

* Governance recommendations
* Compliance interpretations
* Risk-related decisions
* Control implementation decisions
* Audit-related activities

The system is intended to support decision-making and does not replace human judgment.

---

# Monitoring Requirements

The following activities require continuous monitoring:

* System availability
* Response quality
* User feedback
* Model performance
* Incident reporting
* Knowledge base updates
* Vendor service health

---

# Related Governance Artefacts

This document supports:

* AI Use Case Intake Form
* AI System Register
* AI Risk Assessment
* Vendor Risk Assessment
* Human Oversight Plan
* Model Card
* Monitoring Plan
* Incident Response Plan

---

## Document Ownership

| Field            | Value              |
| ---------------- | ------------------ |
| Document Owner   | AI Governance Lead |
| Review Frequency | Annual             |
| Classification   | Internal           |
| Status           | Active             |

---

**Version:** 1.0
**Last Updated:** June 2026
