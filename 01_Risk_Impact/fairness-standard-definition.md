# Definition of Fairness Standards: Aura-Gen Project

This document formalizes the specific mathematical standards used to evaluate the fairness of the Aura-Gen Customer Assistant.

| Standard Type | Metric | Rationale for Selection |
| :--- | :--- | :--- |
| **Primary Standard** | Equal Opportunity (True Positive Rate) | Ensures that all customers who are eligible for a refund under company policy have an equal probability of approval, regardless of demographic. |
| **Secondary Standard** | Demographic Parity (Approval Rate) | Used as a high-level monitoring signal to identify significant deviations in service delivery across different regions. |
| **Acceptable Variance** | < 5% Delta | Any performance gap exceeding 5% between protected groups triggers a mandatory model retraining and root-cause analysis. |
