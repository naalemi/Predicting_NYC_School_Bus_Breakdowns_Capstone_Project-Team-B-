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
![Regression Features](https://github.com/naalemi/TeamB_Predicting_NYC_School_Bus_Breakdowns_and_Delays/blob/56518f40a4719bb4d7ef14f6de3db4391b866f7d/Regression_Model_Top_Features.png)  

**Top Predictor:** Bus_Company_Name
