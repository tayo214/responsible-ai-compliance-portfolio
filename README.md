# Enterprise AI Governance Framework: Aura-Gen Case Study

Welcome to the Aura-Gen AI Governance Repository. This project demonstrates an end-to-end implementation of AI governance and compliance for a high-risk Generative AI system, aligned with ISO/IEC 42001 and the EU AI Act.

## Portfolio Oversight Dashboard
| Metric | Status | Notes |
| :--- | :--- | :--- |
| System Classification | High-Risk | Annex III: Financial & Essential Services |
| Inventory Status | Completed | Fully documented in Phase 0 |
| Risk Assessment | In Progress | Hallucination & Data Privacy deep-dives |
| Human Oversight | Semi-Automated | Escalation thresholds defined |
| Compliance Alignment | EU AI Act | High-risk obligations identified |

## Repository Structure
This portfolio is organized by the AI Lifecycle to demonstrate professional subject matter expertise.

* [Phase 0: Strategy & Inventory](./00_Strategy_Inventory/) - 30-60-90 Day Plan, System Inventory, and Governance Charter.
* [Phase 1: Risk & Impact](./01_Risk_Impact/) - EU AI Act Triage, LLM Risk Assessments, and Threat Modeling.
* [Phase 2: Technical Audit](./02_Technical_Audit/) - Bias Testing, Output Verification, and Failure Pattern Analysis.
* [Phase 3: Operational Monitoring](./03_Monitoring_Response/) - KPI Framework, Incident Playbooks, and Board Reporting.

## Case Study: Aura-Gen Customer Assistant
Aura-Gen is a self-hosted, open-source Generative AI system designed to assist with customer support and refund processing. 

### Why this project?
This case study was chosen to demonstrate the ability to govern a High-Risk AI system that involves:
1. Financial Impact: Automated decision support for refund eligibility.
2. Sensitive Data: Handling customer records using internal-only datasets.
3. Complex Risks: Managing LLM-specific failures like hallucinations and prompt injection.

# Responsible AI Compliance Portfolio: Aura-Gen Case Study

This repository demonstrates an end-to-end **AI Governance and Compliance Framework** for a high-risk Generative AI system. It is aligned with the **EU AI Act**, **GDPR**, and **ISO/IEC 42001** standards.

## 🚀 Project Overview
**System:** Aura-Gen Customer Assistant (High-Risk)  
**Function:** Automated financial refund processing using internal customer data.  
**Objective:** To implement a "Privacy by Design" and "Fairness First" governance lifecycle.

## 📂 Repository Structure
* **`00_Strategy_Inventory/`**: Contains the AI Systems Inventory, Stakeholder Matrix, and the 30-60-90 Day Operational Plan.
* **`01_Risk_Impact/`**: Includes the Data Protection Impact Assessment (DPIA), Fairness Standards, and Accuracy Mitigation strategies.
* **`02_Audit_Testing/`**: Documents Adversarial "Red Team" testing results and continuous monitoring logs.

## 🛠️ Key Governance Achievements
* **Risk Classification:** Identified Aura-Gen as "High-Risk" under the EU AI Act, triggering mandatory fundamental rights assessments.
* **Algorithmic Fairness:** Established an **Equal Opportunity** metric using **Fairlearn** to ensure non-discriminatory refund outcomes across dialects and regions.
* **Privacy Guardrails:** Implemented a **Defense in Depth** strategy, combining database-level data minimization with an external Python-based regex output filter to prevent PII leakage.
* **Strategic Roadmap:** Authored a 90-day execution plan to transition from initial discovery to active board-level KPI reporting.
