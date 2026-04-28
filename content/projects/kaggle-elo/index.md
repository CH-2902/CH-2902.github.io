---
title: "Kaggle — Elo Merchant Recommendation"
date: 2023-12-01
summary: "Predicted customer loyalty for Brazilian payment brand Elo. Gradient boosting on outlier-split data. RMSE 3.6 — top 22.2% (914/4111)."
tags:
  - Gradient Boosting
  - Feature Engineering
  - Kaggle
weight: 50
---

End-to-end Kaggle competition entry: predicting customer-loyalty scores for
Elo (Brazilian payment brand) from raw transaction data.

**What I did**

- **Memory optimisation:** refined dtypes and wrote a custom garbage-collection
  routine to fit the dataset comfortably in working memory.
- **Feature engineering:** extracted temporal trends and holiday-season
  patterns from transaction histories to lift predictive power.
- **Modelling:** trained a **gradient-boosting machine (LightGBM)** on
  outlier vs. non-outlier splits, using gain/split feature-importance to
  prune redundant features.

**Result:** RMSE **3.6** — placed **914 / 4111** (top 22.2%).

**Stack:** Python · Pandas · NumPy · LightGBM.

*Code will be uploaded to GitHub.*
