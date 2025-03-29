# RAVENS-PCA-ANALYSIS

This project explores the use of Principal Component Analysis (PCA) to reduce dimensionality in NFL game data and assess its impact on model performance. We focus on predicting game outcomes for the Baltimore Ravens, comparing classification results with and without PCA.

## Objective

To evaluate how dimensionality reduction via PCA influences the interpretability and accuracy of machine learning models (Random Forest and Logistic Regression) applied to sports analytics.

---

## Methods & Workflow

- Cleaned and encoded categorical data (e.g., team location, weather, betting line).
- Standardized features before applying PCA.
- Retained principal components explaining ≥95% of total variance.
- Used visualization tools: Scree plots, heatmaps, biplots, and 2D projections.
- Trained and compared two classifiers:
  - Random Forest (with and without PCA)
  - Logistic Regression (with and without PCA)

---

## Key Findings

- PCA enabled significant dimensionality reduction while preserving key variance.
- Logistic Regression showed slight improvement with PCA (accuracy ↑ from 0.60 to 0.63).
- Random Forest performed better without PCA (accuracy ↓ from 0.62 to 0.58 with PCA).
- Stadium neutrality and weather temperature emerged as influential predictors.

---

## Tools & Libraries

- Python
- Scikit-learn, Pandas, NumPy
- Matplotlib, Seaborn

---

## ⚠️ Disclaimer

This project was developed for academic purposes and is not affiliated with the NFL or any of its teams.


