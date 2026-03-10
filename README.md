# Data Center Power Consumption Prediction

## Project Overview
This project predicts power consumption in data centers using machine learning.
Environmental conditions and time-based features are used to forecast energy demand.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Machine Learning Pipeline
1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Lag and Rolling Features
5. Model Training (XGBoost)
6. Model Evaluation
7. Future Power Prediction

## Model Performance

Baseline Model:
R² Score: 0.41

Improved Model (with lag features):
R² Score: 0.998  
RMSE: ~243

Lag features significantly improved prediction accuracy by capturing temporal dependencies in power consumption patterns.

## Visualizations

### Power Consumption Trend
![Power Trend](power_trend.png)

### Actual vs Predicted Power
![Prediction Graph](prediction_vs_actual.png)

## Future Prediction Example

Predicted Power Consumption: ~35000 kW

## Future Improvements
- Deep learning models (LSTM)
- Real-time energy monitoring dashboard
- Model optimization

## Author
Karthik

