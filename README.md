# adversiting-data-analysis
# Polynomial Regression

## Project Description

This project demonstrates **Polynomial Regression** using the Advertising dataset.

The main purpose of this project is to understand how polynomial features can be used to model non-linear relationships and interactions between variables.

## Dataset

The dataset contains advertising expenditure and sales information.

### Input Variables

* TV
* radio
* newspaper

### Target Variable

* sales

## Project Steps

The notebook follows these steps:

1. Business Problem Understanding
2. Data Collection
3. Data Understanding
4. Exploratory Data Analysis (EDA)
5. Data Cleaning
6. Data Wrangling
7. Feature and Target Selection
8. Polynomial Feature Transformation
9. Train-Test Split
10. Model Building
11. Prediction
12. Model Evaluation
13. Cross Validation
14. Hyperparameter Tuning
15. Final Model
16. Model Saving and Loading

## Machine Learning Algorithm

**Polynomial Regression**

Polynomial features are generated using `PolynomialFeatures`, followed by `LinearRegression`.

Different polynomial degrees are tested to understand model complexity and performance.

## Evaluation Metrics

The model is evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score
* Cross Validation Score

## Model Deployment Preparation

The final polynomial converter and trained model are saved using Joblib.

```text
polynomial_converter.joblib
sales_poly_model.joblib
```

They can later be loaded and used to make predictions on new advertising data.

## Technologies

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib
* Jupyter Notebook

## Author

Sivadurga Gurrala
