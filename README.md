# Logistics Delivery Time Prediction

## Project
Predict delivery time for logistics orders using machine learning.

## Dataset
The dataset is synthetic and contains 300 logistics orders with:
- distance_km
- package_weight_kg
- traffic_level
- priority_level
- weather_condition
- warehouse_zone
- delivery_time_min (target)

## Models
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Evaluation
MAE, RMSE, R² and 5-fold cross-validation are used.

## Run
```bash
pip install -r requirements.txt
python src/train_model.py
```

Results are written to `results/`.

## Optimization Ideas
Use predictions to prioritize delayed deliveries, allocate vehicles, improve route planning, and reduce avoidable delivery time.
