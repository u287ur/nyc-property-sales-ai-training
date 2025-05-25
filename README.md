🌍 Available Languages:
[🇺🇸 English](README.md) | [🇹🇷 Türkçe](README.tr.md)

# NYC Property Sales Price Prediction

This repository aims to predict property sales prices in New York City using machine learning. The project uses the "NYC Property Sales" dataset from Kaggle. Different regression algorithms (Ridge, XGBoost) were applied and their results compared.

# Introduction

In this project, property sales data from New York City is analyzed to predict the sale price of a property.  
Dataset used: [Kaggle - NYC Property Sales](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales)

Main steps performed:
- Data cleaning and preprocessing (handling missing values, outliers, type conversions)
- Feature engineering (one-hot encoding, target encoding, new variables)
- Train/test split
- Prediction using Ridge and XGBoost regression models
- Model evaluation and comparison

Technical details and code explanations are provided in the markdown cells within the notebook file.

# Metrics

Model performance was evaluated using the following metrics:
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² score

Results obtained:
- **Ridge Regression R²:** 0.43
- **XGBoost Regression R²:** 0.66

According to the results, the XGBoost model achieved higher performance.  
Model performance improved especially with target encoding to capture location-based price differences.

# Conclusion and Future Work

This study provides a basic machine learning approach for predicting sales prices in the NYC real estate market.  
In the future, the following improvements can be made to increase model performance:
- Including more categorical variables (e.g., neighborhood, building type)
- More comprehensive feature selection and hyperparameter optimization
- Deploying the model with a web interface for end users
- Trying time series analysis or different regression algorithms

# Links

- [Kaggle - NYC Property Sales Dataset](https://www.kaggle.com/datasets/new-york-city/nyc-property-sales)
- [Code (Kaggle)](https://www.kaggle.com/code/u287ur/nyc-property-sales-price-prediction)