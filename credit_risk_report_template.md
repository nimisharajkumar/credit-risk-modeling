# Credit Risk Modeling — Project Report

## Executive summary
This project demonstrates a supervised classification workflow for simulated loan default outcomes. The data is synthetic and results are for educational demonstration only.

## Business problem
Describe how predicting potential defaults may support risk review, while noting that model outputs should not replace lending policy or human review.

## Dataset
- File: `data/credit_risk_synthetic.csv`
- Rows: 3,500 synthetic loan records
- Target: `default` (1 = simulated default; 0 = simulated non-default)
- Inputs: loan amount, income, interest rate, debt-to-income ratio, employment history, credit history, prior delinquencies, home ownership, and loan purpose.
- Missing values are intentionally present to demonstrate preprocessing.

## Methodology
1. Data quality checks and exploratory analysis.
2. Stratified train/test split.
3. Median/mode imputation, scaling, and one-hot encoding in a pipeline.
4. Comparison of Logistic Regression, Decision Tree, and Random Forest.
5. Evaluation with accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.
6. Permutation importance for model interpretation.

## Results
Run the notebook and insert the model comparison table and confusion matrix here. Do not report results before running the notebook.

## Recommendations
Discuss the precision/recall trade-off and why model thresholds depend on the lender's risk tolerance and the cost of errors.

## Limitations and responsible use
The dataset is synthetic and is not suitable for real lending decisions. A real system would need representative data, validation, calibration, fairness and legal review, monitoring, and human oversight.
