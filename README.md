# House Price Prediction using Machine Learning

## Project Overview

This project focuses on predicting house prices using Machine Learning techniques based on property-related features such as house size, number of bedrooms, location index, and property age.

The project demonstrates a complete regression workflow including:

* Data exploration and visualization
* Data preprocessing
* Feature scaling
* Model training using Linear Regression
* Model evaluation and prediction analysis

---

## Objective

The primary objective of this project is to build a predictive model capable of estimating house prices accurately using housing features and regression techniques.

---

## Dataset Information

The dataset contains structured housing information with the following features:

### Features:

* **Size** — Area of the house in square feet
* **Bedrooms** — Number of bedrooms
* **Location_Index** — Numerical representation of location quality
* **Age** — Age of the property
* **Price** — House price (Target Variable)

---

## Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Workflow

### 1. Data Loading & Exploration

* Loaded the dataset using Pandas
* Inspected dataset structure and data types
* Generated summary statistics
* Checked for missing values

### 2. Exploratory Data Analysis (EDA)

Performed visual analysis including:

* Correlation heatmap
* Pairplot visualization
* Relationship analysis between features and target variable

These visualizations helped identify strong correlations and feature importance affecting house prices.

---

## Data Preprocessing

The preprocessing pipeline included:

* Handling missing values using median imputation
* Splitting features and target variables
* Feature scaling using `StandardScaler`
* Train-test split for model validation

---

## Machine Learning Model Used

### Linear Regression

A Linear Regression model was trained to predict house prices based on the input housing features.

The model learns the relationship between:

* Property size
* Number of bedrooms
* Location quality
* Property age

and predicts the expected house price.

---

## Model Evaluation Metrics

The model was evaluated using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

### Model Performance

* **R² Score:** ~0.997
* The model achieved very high prediction accuracy on the dataset.

---

## Visualizations Included

* Correlation Heatmap
* Pairplot of housing features
* Actual vs Predicted house prices scatter plot

These visualizations help understand:

* Feature relationships
* Data distribution
* Prediction performance

---

## Project Structure

```bash id="3m8xqk"
├── Housing_data.csv
├── House_Price_Prediction.ipynb
├── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```bash id="l3j8we"
git clone <repository-link>
```

### 2. Install Required Libraries

```bash id="c4n9xp"
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run the Jupyter Notebook

```bash id="m1v9zx"
jupyter notebook
```

---

## Future Improvements

* Implement advanced regression models such as:

  * Random Forest Regressor
  * XGBoost Regressor
  * Gradient Boosting Regressor
* Perform feature engineering
* Add hyperparameter tuning
* Build a web application using Flask or Streamlit
* Deploy the model for real-time house price prediction

---

## Conclusion

This project demonstrates how Machine Learning regression techniques can be applied to predict house prices effectively. The Linear Regression model achieved strong performance, and the project provides a complete end-to-end workflow for housing price prediction.

---
