# Minjoo (Mia) Sung · Fraud & Risk Analytics

I find abusive accounts and risky activity in data, then turn what investigations reveal into detection rules, models, and better risk decisions.

About five years across banking AML/KYC (HSBC, SMBC, Bank of Communications), a global crypto exchange (ProBit Global), and a U.S. digital bank (Monzo). M.S. in Business Analytics, USC Marshall.

---

## What I work on

- **Investigations → detection:** account takeover and linked-account analysis with device, IP, and transaction signals; turning recurring patterns into rules and onboarding checks
- **Detection quality:** tuning rule conditions and thresholds against investigation outcomes, while checking that known fraud is still caught
- **Metric integrity:** tracing risk metrics back to source tables, fixing loss definitions, and validating numbers before they reach leadership
- **Modeling:** feature engineering for identity linkage, velocity, and recency; supervised (LightGBM) and unsupervised (PCA + autoencoder) fraud scoring

## Selected work highlights

*Professional work. No confidential data is published here.*

- Reduced non-actionable alerts by 35% within targeted rules across a portfolio of 20+ fraud rules, verifying that known fraud was still detected (crypto exchange)
- Expanded account-takeover investigations to linked accounts using SQL; set account-level withdrawal restrictions based on combined evidence rather than a single shared signal
- Rebuilt a fraud-loss methodology across three source datasets, correcting reported losses by 35%; validated seven risk metrics (U.S. digital bank)
- Backtested a vendor fraud score across 27K+ onboarding applications with Data Science and recommended targeted verification over automatic rejection
- Used Claude Code, Cursor, and Gemini CLI with BigQuery for query work, plus independent recalculation to validate report figures

## Projects (USC Marshall, Fraud Analytics)

| Project | What it shows | Result |
|---|---|---|
| [Application Fraud Detection](https://github.com/minjoos/application_fraud_detection) | Placeholder cleanup to prevent false identity links, 1,500+ linkage/velocity features, KS + forward selection, 5-model comparison | 61.2% of fraud captured in top 3% (OOT) |
| [Card Transaction Fraud Detection](https://github.com/minjoos/credit-card-fraud-detection) | 2,600+ behavioral and velocity features across 0–60 day windows, LightGBM | 57.2% of fraud captured in top 3% (OOT) |
| [NYC Property Anomaly Detection](https://github.com/minjoos/nyc-property-anomaly-detection) | Unsupervised scoring with no labels: peer-normalized features, PCA distance + autoencoder, explainable review queue | 1.04M records ranked; top-10K queue |

All three are academic projects on course or public data, not production systems.

## Tools

**Analysis:** SQL (BigQuery, CTEs, window functions) · Python (pandas, scikit-learn, LightGBM) · dbt (code review) · Looker · Tableau
**AI-assisted workflow:** Claude Code · Cursor · Gemini CLI
**Investigation:** Chainalysis · World-Check · Jira

## Contact

[LinkedIn](https://www.linkedin.com/in/minjoosung) · mia.sung.us@gmail.com
