# Explainable Machine Learning for Early Bankruptcy Prediction

A financial risk analytics project using statistical learning, ensemble models, and explainable AI to identify potential corporate bankruptcy risk.

## Overview

This project investigates early bankruptcy prediction using the Taiwan Bankruptcy Dataset. It compares machine learning classifiers on a highly imbalanced classification problem and explores how SHAP can help interpret model predictions.

## Research Objectives

- Predict corporate bankruptcy risk using financial indicators.
- Compare statistical and machine learning classification models.
- Address class imbalance using techniques such as SMOTE and cost-sensitive learning.
- Evaluate models using precision, recall, F1-score, ROC-AUC, and other relevant metrics.
- Interpret model predictions using SHAP (SHapley Additive exPlanations).

## Models Evaluated

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Voting Classifier

## Reported Findings

According to the accompanying research paper:

- **XGBoost:** ROC-AUC of 0.9499 and accuracy of 0.9626.
- **Logistic Regression:** Highest reported recall of 0.7955, illustrating the importance of evaluating minority-class detection rather than accuracy alone.
- **Key risk indicators:** Leverage, liquidity, profitability, and cash-flow measures.

*These are reported research-paper results; they should be independently verified against the notebook before treating them as reproduced results.*

## Repository Structure

- `bankruptcy_prediction.ipynb` — Jupyter notebook containing the analysis.
- `Research paper.pdf` — accompanying research paper.
- `.gitignore` — files excluded from version control.

## Tools and Techniques

Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, XGBoost, SMOTE, and SHAP.

## Limitations

The study uses the Taiwan Bankruptcy Dataset. Results may not generalize to other countries, industries, or time periods. Further validation is needed before real-world financial decision-making.

## Research Paper

See `Research paper.pdf` for the full methodology, model comparison, analysis, and conclusions.

## Author

Nandini Mukherjee  
BSc Data Science and Statistics, CHRIST (Deemed to be University), Bengaluru
