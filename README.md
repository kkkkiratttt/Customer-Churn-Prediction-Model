# Customer Churn Prediction using Machine Learning

## Project Overview

This project is a Machine Learning based Customer Churn Prediction System developed using Python and Scikit-learn. The model predicts whether a telecom customer is likely to leave the service (Churn) or continue using it based on customer and service-related data.

The project uses the Logistic Regression classification algorithm and includes data preprocessing, feature encoding, model training, prediction, and performance evaluation.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* One-Hot Encoding
* Train-Test Split
* Logistic Regression Model
* Accuracy Evaluation
* Confusion Matrix
* Classification Report

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn

---

## Machine Learning Algorithm

* Logistic Regression

---

## Dataset Information

The dataset contains telecom customer information including:

* Gender
* Senior Citizen Status
* Internet Service
* Contract Type
* Monthly Charges
* Total Charges
* Payment Method
* Churn Status

---

## Project Workflow

1. Upload and load dataset
2. Data cleaning and preprocessing
3. Feature selection
4. Convert categorical values into numerical data
5. Split dataset into training and testing sets
6. Train Logistic Regression model
7. Predict customer churn
8. Evaluate model performance

---

## Model Performance

The Logistic Regression model achieved approximately **78% accuracy** in predicting customer churn.

---

## Libraries Used

```python
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, confusion_matrix, classification_report
```

---

## How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the `Customer.csv` dataset.
3. Run all cells sequentially.
4. View predictions and evaluation metrics.

---

## Repository Structure

```text
Customer-Churn-Prediction/
│
├── Customer.csv
├── Customer_Churn_Prediction_Notebook.ipynb
├── README.md
└── presentation.pptx
```

---

## Conclusion

This project demonstrates how Machine Learning can help telecom companies predict customer churn and improve customer retention strategies using customer behavior data.
