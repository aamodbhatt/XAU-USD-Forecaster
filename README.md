# XAU-USD Close Value Forecasting

This project demonstrates the development of a forecasting model for predicting the XAU-USD close value using the `ForecasterAutoreg` class from the `skforecast` library with a `DecisionTreeRegressor` as the underlying model.

## Workflow Overview

1. **Data Preparation**  
   - Loaded and formatted the dataset, set the date column as the index, and filled missing values.

2. **Feature Engineering**  
   - Created lagged variables and additional features to capture temporal dependencies.

3. **Train-Test Split**  
   - Defined training and testing periods for model evaluation.

4. **Model Tuning**  
   - Performed a grid search to optimize hyperparameters and select the best number of lags.

5. **Model Fitting**  
   - Trained the model on the training data.

6. **Prediction and Evaluation**  
   - Predicted test data and compared actual vs. predicted values.

## Results

The model successfully captured trends in the XAU-USD close value, showing close alignment between actual and predicted values during the test period.

### Future Improvements

- Experiment with different regressors.
- Add more features.
- Explore advanced hyperparameter tuning.
