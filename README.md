# Predicting Medical Insurance Costs

Data Science & Machine Learning group project — INFNOVA Academy Summer Boot Camp 2026.

## Team
Kalkidan Tekle (Lead), Bezawit Alemayehu, Makda Yirgaye, Sarasiah Munene Kanelo, Onnelie Mathendele, Bereket Tadesse

## Project Overview
We analyze a medical insurance cost dataset (1,338 individuals) to understand what drives insurance charges, then build two models:
1. **Regression** — predict the exact charge (Linear Regression vs. Random Forest)
2. **Classification** — predict smoker status from patient data (Logistic Regression)

## Files
- `insurance_medical_cost.csv` — raw dataset
- `insurance_medical_cost_cleaned.csv` — cleaned dataset
- `Medical_prediction.ipynb` — full analysis: EDA, visualizations, both prediction models, and conclusion
- `Medical_Insurance_Prediction.pptx` — final presentation slides

## Key Results
- Random Forest regression: R² = 0.983, MAE = $1,328
- Logistic Regression classifier (smoker status): 100% accuracy, precision, recall
- Smoking status is the single strongest driver of medical charges (correlation ≈ 0.93)
