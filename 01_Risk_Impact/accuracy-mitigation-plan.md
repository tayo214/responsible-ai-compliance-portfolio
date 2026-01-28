# Accuracy & Hallucination Mitigation Plan: Aura-Gen

This document outlines the technical and procedural controls implemented to ensure the financial accuracy of the Aura-Gen Customer Assistant.

## 1. Grounding and Context
* **Retrieval-Augmented Generation (RAG):** The system is prohibited from answering refund queries without first retrieving the latest 'Global Refund Policy' document.
* **Source Attribution:** Every approval or denial must include a link or snippet of the specific policy section used.

## 2. Thresholds for Human Intervention
* **Confidence Scores:** Any decision with a confidence score below 85% is automatically routed to a Human-in-the-Loop (HITL) for review.
* **Financial Caps:** Any refund over $100 requires mandatory manual sign-off by a Finance Lead.

## 3. Continuous Validation
* **Golden Dataset Testing:** A monthly audit comparing 100 bot decisions against 100 human-expert decisions to measure 'Drift' and accuracy rates.
