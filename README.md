# Minjoo (Mia) Sung · Senior Fraud & Risk Analyst

Fraud detection, risk analytics, and identity & payments risk, built on SQL/BigQuery and grounded in hands-on investigations.

5+ years across a U.S. digital bank (Monzo US), a global crypto exchange (ProBit Global), and banking financial-crime roles (HSBC, SMBC, Bank of Communications). M.S. in Business Analytics, USC Marshall.

---

## What I work on

- **Fraud detection & rule quality:** owning rule portfolios, tuning signal combinations and thresholds against investigation outcomes, and cutting non-actionable alerts while known fraud is still caught
- **Identity & onboarding risk:** evaluating vendor scores and onboarding decisions against downstream fraud, balancing fraud capture, review volume, and customer friction
- **Payments risk & root-cause analysis:** tracing anomalies to their source in BigQuery and partnering with Engineering through remediation
- **Metric integrity:** rebuilding loss methodology, tracing risk metrics to source tables, and validating numbers before they reach leadership
- **Investigations → controls:** account-takeover and linked-account analysis with device, IP, behavioral, and transaction signals, turned into scalable onboarding controls

## Selected work highlights

*Professional work. No confidential data is published here.*

**Monzo US**
- Rebuilt U.S. fraud-loss methodology in BigQuery across chargebacks, recoveries, write-offs, and negative balances; corrected a 35% overcount in reported losses
- Backtested a vendor fraud score across 27K+ onboarding applications with Data Science; recommended targeted verification and manual review rather than automatic rejection
- Traced a negative-balance spike to an ACH return-file issue blocking ~250 valid returns; partnered with Engineering on remediation
- Validated seven fraud and operations metrics across BigQuery and Looker, uncovering a 26% understatement in fraud cost per active customer

**ProBit Global**
- Owned and refined 20+ active fraud rules; reduced non-actionable alert volume by 35% within a targeted rule set while verifying that known fraud was still detected
- Expanded account-takeover investigations to linked accounts using SQL; evidence-based restrictions reduced at-risk withdrawal exposure by 43% across investigated accounts
- Translated linked-account patterns into device, IP, behavioral, and session-based onboarding controls

## Projects (USC Marshall, Fraud Analytics)

| Project | What it shows | Result |
|---|---|---|
| [Application Fraud Detection](https://github.com/minjoos/application_fraud_detection) | Placeholder cleanup to prevent false identity links, 1,500+ linkage/velocity features, KS + forward selection, 5-model comparison | 61.2% of fraud captured in top 3% (OOT) |
| [Card Transaction Fraud Detection](https://github.com/minjoos/credit-card-fraud-detection) | 2,600+ behavioral and velocity features across 0–60 day windows, LightGBM | 57.2% of fraud captured in top 3% (OOT) |
| [NYC Property Anomaly Detection](https://github.com/minjoos/nyc-property-anomaly-detection) | Unsupervised scoring with no labels: peer-normalized features, PCA distance + autoencoder, explainable review queue | 1.04M records ranked; top-10K queue |

All three are academic projects on course or public data, not production systems.

## Tools

**Analysis:** SQL (BigQuery, CTEs, window functions) · Python (pandas, scikit-learn, LightGBM) · dbt (code review) · Looker · Tableau
**AI-assisted workflow:** Claude Code · Cursor · Gemini CLI for query work, with independent recalculation to validate report figures
**Investigation:** Chainalysis · World-Check · Jira

## Contact

[LinkedIn](https://www.linkedin.com/in/minjoosung) · mia.sung.us@gmail.com
