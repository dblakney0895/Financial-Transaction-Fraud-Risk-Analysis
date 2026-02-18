# Executive Summary — Fraud Risk Analysis

This project explores transaction data to identify patterns associated with fraudulent activity and summarize risk indicators that can support monitoring and investigation workflows.

## What was done
- Measured fraud prevalence and reviewed class imbalance
- Compared fraud vs non-fraud transaction behavior (amounts, time patterns, feature distributions)
- Identified high-risk indicators using explainable rules (baseline risk scoring)
- Documented ethical risks including false positives, bias, and privacy concerns

## Key takeaways
- Fraud is typically rare, requiring careful evaluation methods
- Certain features and behaviors can signal higher risk
- Transparent baseline scoring can provide quick wins before advanced ML models

## Recommended next steps
- Add model-based classification (logistic regression)
- Evaluate precision/recall and cost-based thresholds
- Establish governance controls and review process for flagged transactions
