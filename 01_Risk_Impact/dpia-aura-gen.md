# Data Protection Impact Assessment (DPIA): Aura-Gen

This assessment evaluates the impact of the Aura-Gen system on data privacy and outlines the controls implemented to protect customer information.

| Section | Assessment |
| :--- | :--- |
| **Data Types Processed** | Name, Email, Transaction History, Masked Payment Info. |
| **Legal Basis** | Contractual Necessity (Processing requested refunds). |
| **Primary Risk** | Accidental disclosure of PII through model output or logging. |
| **Mitigation Strategy** | **Data Minimization:** PII masking (e.g., Credit Card XXXX-XXXX-XXXX-1234) is applied at the database layer before the AI receives the data. |
| **Data Retention** | Chat logs are purged after 90 days unless flagged for a manual audit. |
