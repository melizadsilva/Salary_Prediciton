# Salary Prediction Using Years of Experience

This project implements a simple linear regression model to predict salary based on years of experience. The model uses `years of experience` as the independent variable to predict the dependent variable, `salary`.

## Project Overview

The goal of this project is to create a predictive model that estimates a person's salary based on their years of experience. The linear regression model is built using the following equation:

`Salary`= 24380.20 + 9423.82 * `Years of Experience`


Where:
- **Intercept** = 24380.20 (The predicted salary when years of experience is zero)
- **Coefficient** = 9423.82 (The increase in salary for each additional year of experience)

## Evaluation Metrics

- **Mean Absolute Error (MAE)**: 6286.45  
  This metric represents the average absolute difference between the predicted and actual salary values.

- **Mean Squared Error (MSE)**: 49,830,096.86  
  This metric gives an indication of the model's overall error, with larger errors penalized more heavily.

- **R-squared**: 0.9024 (or 90.24%)  
  This indicates that approximately 90.24% of the variance in the salary data is explained by the years of experience.

## Dependencies

- Python 3.x
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
