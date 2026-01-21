# JMG Used Car Pricing Strategy

This repository contains the solutions for **MIS710 Assignment 1**, focusing on the development of a pricing model for used cars in the **US market** using machine learning.

## Business Understanding

Jason Motors Group (JMG) aims to predict used car prices more accurately to improve pricing strategies, reduce holding times, and increase margins. The dataset provided contains listings of used cars from **Craigslist**, which includes key features like car make, model, odometer reading, and condition.

## Data Overview

The dataset contains over 58,000 car listings with the following key attributes:
- **Make**: Manufacturer of the car.
- **Model**: Specific model of the car.
- **Listed_Price**: Price of the car.
- **Odometer**: Mileage of the car.
- **Condition**: Condition rating of the car.
- **Fuel_Type**: Type of fuel the car uses.

## Machine Learning Approach

The assignment involved the development of two models:
1. **Linear Regression**: A baseline model to predict prices.
2. **Random Forest Regressor**: A non-linear ensemble model to predict prices.

### Model Evaluation:
- **Linear Regression**: R² = 0.32
- **Random Forest Regressor**: R² = 0.77

The **Random Forest Regressor** model outperformed the linear regression model, and it is recommended for future deployment.

## Files in this Repository

- **MIS710A1_Sachdeva_224850909.pdf**: Business report summarizing the findings and recommendations.
- **MIS710A1_Sachdeva_224850909.ipynb**: Jupyter notebook with the data exploration, preprocessing, and model development.
- **MIS710A1_Sachdeva_224850909_Python.pdf**: A PDF version of the Jupyter notebook.
- **JMG_data.csv**: The dataset used for model development.
- **JMG_comp.csv**: A competition dataset (used to apply the trained model).
- **JMG_metadata.pdf**: Metadata describing the dataset.

## Conclusion

This model will assist JMG in making more informed pricing decisions and improve their overall business operations in the used car market.
