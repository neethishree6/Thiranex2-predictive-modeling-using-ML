# COVID-19 Predictive Modeling Using Machine Learning

## Project Overview

This project focuses on building predictive machine learning models using COVID-19 datasets. The project includes data preprocessing, feature engineering, model training, evaluation, and visualization using Python libraries.

The goal is to predict confirmed COVID-19 cases using supervised machine learning algorithms and analyze model performance using evaluation metrics and visualizations.

---

## Objectives

* Clean and preprocess COVID-19 datasets
* Handle missing values and duplicates
* Perform feature engineering
* Train machine learning models
* Evaluate model accuracy and performance
* Visualize model results and feature importance

---

## Datasets Used

The following datasets were used in this project:

1. `covid_19_india.csv`
2. `covid_vaccine_statewise.csv`
3. `StatewiseTestingDetails.csv`

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

### Tools

* Jupyter Notebook
* Git
* GitHub

---

## Machine Learning Algorithms Used

### 1. Linear Regression

Used for predicting confirmed COVID-19 cases based on numerical features.

### 2. Decision Tree Regressor

Used to create rule-based prediction models.

### 3. Random Forest Regressor

An ensemble learning algorithm used for improving prediction accuracy.

---

## Features Used for Prediction

* Day
* Month
* Year
* Deaths
* Cured Cases

### Target Variable

* Confirmed Cases

---

## Data Preprocessing Steps

* Handled missing values
* Removed duplicates
* Converted date columns
* Performed feature engineering
* Prepared training and testing datasets

---

## Model Evaluation Metrics

### Mean Absolute Error (MAE)

Measures average prediction error.

### Root Mean Squared Error (RMSE)

Measures magnitude of prediction error.

### R2 Score

Measures model accuracy and performance.

---

## Visualizations Included

* Model Comparison Bar Chart
* Actual vs Predicted Scatter Plot
* Feature Importance Graph

---

## Project Structure

```text
Thiranex2-predictive-modeling-using-ML/
│
├── dataset/
│
├── cleaned_data/
│
├── visuals/
│
├── reports/
│
├── predictive_model_ML.ipynb
│
├── README.md
│
└── .gitignore
```

---

## Key Findings

* Random Forest Regressor achieved the best performance among all models.
* Deaths and cured cases strongly influenced confirmed case prediction.
* Feature engineering improved prediction quality.

---

## Expected Outcome

This project helps in understanding:

* Supervised Machine Learning
* Regression Algorithms
* Model Training and Testing
* Performance Evaluation
* Data Visualization
* Real-world Data Analytics Workflows

---

## Conclusion

The project successfully demonstrated predictive modeling using COVID-19 datasets. Multiple machine learning algorithms were trained and evaluated, and Random Forest Regressor showed the best performance. This project improved practical understanding of data preprocessing, supervised learning, and model evaluation techniques.

---

## Future Improvements

* Add more advanced ML models
* Use deep learning approaches
* Deploy models using Streamlit or Flask
* Build interactive dashboards
* Perform time-series forecasting
