# ⚡ Predicting Breakdown vs Delay (Classification)

## 🎯 Goal
Predict whether a school bus incident will be a **breakdown** or **running late**.

## ⚙️ Model
- **Algorithm:** XGBoost Classifier
- **Technique:** SMOTE oversampling for class balance
- **Target Classes:**
  - `0` = Running Late
  - `1` = Breakdown

## 📈 Performance
- **Overall F1-score:** 97%
- **Running Late:** Precision & Recall ≈ 99%
- **Breakdown:** Precision ≈ 73%, Recall ≈ 82%

**Feature Importance:**  
![Classification Features](Classification_Model_Top_Features.png)  

XGBoost outperformed alternatives like Balanced Random Forest, especially for recall on the Breakdown class.
