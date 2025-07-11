# ⚡ Electricity Bill Prediction

## 📌 Overview
This project aims to predict electricity bills based on user input such as home appliances, city, company, usage hours, and tariff rate. The model uses a dataset containing appliance usage patterns and location-specific electricity providers to estimate monthly bills. An interactive UI built with `ipywidgets` allows real-time user input and prediction within a Jupyter notebook environment.
<img width="866" height="308" alt="UI1" src="https://github.com/user-attachments/assets/80324918-c9e2-407c-8101-f24d10cd7015" />
<img width="610" height="323" alt="UI2_prediction" src="https://github.com/user-attachments/assets/218f880e-18be-4915-b90d-548c02ccf8d4" />



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

  <img width="878" height="341" alt="MPC2" src="https://github.com/user-attachments/assets/554d33be-e453-49eb-bb9b-7882e4a5875f" />
  <img width="869" height="356" alt="ModelPredcomp" src="https://github.com/user-attachments/assets/d8591b77-8e0f-4dcd-b5d1-112ff372c986" />
  <img width="316" height="335" alt="MCP3" src="https://github.com/user-attachments/assets/2f00d200-0bf6-4085-97c0-d148d6a4429b" />




  

