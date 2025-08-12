# 📏 Predicting Delay Minutes (Regression)

## 🎯 Goal
Predict how many minutes a bus will be delayed.

## ⚙️ Model
- **Algorithm:** Random Forest Regressor
- **Target:** `Delay_Minutes`
- **Features:** Reason, Bus_Company_Name, Run_Type, School_Year, Borough, etc.

## 📈 Performance
- **RMSE:** ~9.65 minutes
- **R²:** ~82%
- Predictions are generally within 10 minutes of actual delay.

**Feature Importance:**  
![Regression Features](Regression_Model_Top_Features.png)

**Top Predictor:** Bus_Company_Name
