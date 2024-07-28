# Module 12 Report Template

## Overview of the Analysis
The purpose of this analysis is to develop a machine learning model that can predict the creditworthiness of borrowers using a dataset of historical lending activity from a peer-to-peer lending services company. By accurately predicting whether a loan will be healthy (low risk) or high-risk, the company can make more informed lending decisions, potentially reducing defaults and improving overall financial stability.

Results

IHere’s a revised version of the summary:

---

**Results:**

The logistic regression model was evaluated using various performance metrics on a test dataset, yielding the following key results:

**Overall Accuracy:** 99.2%

- **Class 0 (Healthy Loans):**
  - **Precision:** 100% (No false positives; all predicted healthy loans are indeed healthy)
  - **Recall:** 99% (Nearly all actual healthy loans are correctly identified)
  - **F1-Score:** 100% (Reflects excellent balance between precision and recall)

- **Class 1 (High-Risk Loans):**
  - **Precision:** 85% (Some false positives; 85% of predicted high-risk loans are actually high-risk)
  - **Recall:** 91% (High true positive rate; 91% of actual high-risk loans are correctly identified)
  - **F1-Score:** 88% (Indicates strong overall performance in identifying high-risk loans)

**Justification for Recommendation:**

The logistic regression model is recommended for use based on the following considerations:

1. **High Overall Accuracy:** With an accuracy of 99.2%, the model correctly classifies the vast majority of loans.
2. **Balanced Performance:** The model demonstrates strong and balanced predictive power for both healthy and high-risk loans, ensuring reliable and robust performance across different loan categories.

## Summary

The logistic regression model demonstrated high accuracy (99.2%) in classifying loans, with excellent performance for both healthy (Class 0) and high-risk (Class 1) loans. For healthy loans, the model achieved 100% precision and a 99% recall, indicating no false positives and very few false negatives. For high-risk loans, the model had an 85% precision and a 91% recall, showing a good balance between correctly identifying high-risk loans and minimizing false positives. The model is recommended due to its reliable and balanced predictions for both loan types.
