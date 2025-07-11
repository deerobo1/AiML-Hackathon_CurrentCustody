# ⚡ Electricity Bill Prediction

## 📌 Overview
This project aims to predict electricity bills based on user input such as home appliances, city, company, usage hours, and tariff rate. The model uses a dataset containing appliance usage patterns and location-specific electricity providers to estimate monthly bills. An interactive UI built with `ipywidgets` allows real-time user input and prediction within a Jupyter notebook environment.

## 🤖 Model Summary

Three supervised regression models were trained and evaluated:

1. **Linear Regression**: 
   - Simple baseline model assuming a linear relationship.
   - Fast and interpretable but less accurate on complex data.

2. **Random Forest Regressor**:
   - Ensemble of decision trees.
   - Captures non-linear relationships and interactions.
   - Strong default model for tabular data.

3. **XGBoost Regressor**:
   - Gradient boosting model.
   - Often provides the best performance in terms of accuracy and generalization.
   - More complex but powerful on structured data.

Each model was evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.

## 📈 Results

The models were compared on the test set. Based on R² Score and RMSE:

- **XGBoost Regressor** performed best in capturing the patterns in electricity consumption.
- **Random Forest** was close behind, offering a good balance of performance and simplicity.
- **Linear Regression** had the lowest accuracy, serving as a basic baseline model.

