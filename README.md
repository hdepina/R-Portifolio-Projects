# Prediction Model Using Random Forest (R)

This project demonstrates how to build and evaluate a Random Forest classification model using R to predict whether a user will download a mobile app after clicking on an ad.

## 📊 Project Summary

- **Language:** R
- **Libraries Used:** `randomForest`, `caret`, `pROC`
- **Dataset:** Simulated ad-click data (100,000 observations)
- **Goal:** Predict the likelihood of a user downloading an app

## 🔍 Key Steps

- Data cleaning and preparation
- Feature selection and factor conversion
- Train/test split using `caret`
- Random Forest model training with variable importance tracking
- Model evaluation via accuracy, confusion matrix, and ROC/AUC

## 📈 Results

- **Accuracy:** ~99.8%
- **Top Predictors:** `app_id`, `channel_id`
- **Insights:** Ad performance is strongly influenced by the app and channel used

## 📎 Files Included

- `Prediction Model APP Analysis.pdf` — Full project write-up with code, outputs, and interpretations

## 🧠 Key Takeaways

- Random Forests provide high predictive accuracy with interpretable feature importance.
- Class imbalance remains a challenge, highlighted by lower specificity despite high overall accuracy.

---

**Author**: Harry Depina  
**Tools Used**: R, RStudio (optional), caret, randomForest, pROC  
**Date**: 2025
