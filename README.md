# Task3
# Day 3: Simple and Linear Regression 

## Objective

This project involves implementing **Simple and Multiple Linear Regression** using the **Housing Price Prediction** dataset. The goal is to predict house prices based on features such as area, number of bedrooms, and bathrooms and task includes data preprocessing, model training, evaluation, and visualization.

---

## Dataset

- **File:** `Housing.csv`
- **Location:** `/kaggle/input/housing-price-prediction/Housing.csv`
- **Target Variable:** `price`
- **Features Used:** `area`, `bedrooms`, `bathrooms`

---

## Libraries Used

- Python 
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Steps Followed

1. **Import and Load Dataset**
    - Used `pandas` to read the CSV file.
2. **Exploratory Data Analysis (EDA)**
    - Checked data types and summary statistics.
    - Handled missing values (if any).
3. **Preprocessing**
    - Selected numeric features (`area`, `bedrooms`, `bathrooms`).
    - Encoded categorical variables if required.
4. **Train-Test Split**
    - Split data using `train_test_split` (80% train, 20% test).
5. **Model Training**
    - Trained `LinearRegression` model from `sklearn`.
6. **Evaluation**
    - Evaluated model using MAE, MSE, and R² Score.
7. **Visualization**
    - Plotted Actual vs Predicted prices.
8. **Interpretation**
    - Displayed model coefficients and intercept.
