# Credit Risk Modeling — Loan Default Prediction

## Overview
A beginner-friendly machine learning project that demonstrates how a lender might analyze historical loan attributes to classify simulated default risk.

## Important data disclosure
**The included dataset is synthetic and generated for demonstration.** It does not represent actual LendingClub data, actual borrowers, or real lending outcomes. Results must not be used for real credit decisions.

## Objectives
- Inspect and clean loan data.
- Explore default patterns using charts.
- Build Logistic Regression, Decision Tree, and Random Forest classifiers.
- Compare accuracy, precision, recall, F1-score, and ROC-AUC.
- Interpret predictive signals using permutation importance.
- Discuss class imbalance, leakage, fairness, and limitations.

## Repository structure
```text
credit-risk-modeling/
├── data/credit_risk_synthetic.csv
├── results/                 # Add exported metrics/figures here after running
├── reports/                 # Add final report here
├── credit_risk_analysis.ipynb
├── requirements.txt
└── README.md
```

## Run locally
1. Install Python 3.10+.
2. Create and activate a virtual environment (recommended).
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open Jupyter and run `credit_risk_analysis.ipynb` from top to bottom.

The notebook uses a fixed random seed and a held-out test set. Preprocessing is fitted within a pipeline to reduce data leakage.

## Key metrics
- **Precision:** Of predicted defaults, the proportion that were defaults in the dataset.
- **Recall:** Of actual defaults in the test set, the proportion identified by the model.
- **F1-score:** Harmonic mean of precision and recall.
- **ROC-AUC:** Ranking/separation performance across thresholds.
- **Confusion matrix:** Counts of true and false predictions.

## Limitations and responsible use
Synthetic data can be useful for practicing a workflow but cannot establish real-world performance. Real credit decision systems require representative data, careful validation, calibration, fairness and legal review, monitoring, and human oversight. Feature importance is predictive, not causal.

## Author
Add your name and internship details here before publishing.
