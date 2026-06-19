# House Price Prediction Project 🏠

## Project Overview

This project uses Machine Learning techniques to predict house prices based on different house features. The dataset was cleaned, analyzed, visualized, and used to build predictive models.

The main goal of this project is to identify the factors that influence house prices and compare the performance of two machine learning algorithms.

---

## Objectives

* Load and explore the house price dataset.
* Clean and preprocess the data.
* Handle missing values and duplicate records.
* Convert categorical data into numerical format.
* Build prediction models.
* Compare Linear Regression and Random Forest Regressor.
* Visualize important relationships in the data.
* Generate insights and business recommendations.

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset Features

The dataset contains information about houses, such as:

* Area
* Number of bedrooms
* Number of bathrooms
* Number of stories
* Main road access
* Guest room availability
* Basement availability
* Hot water heating
* Air conditioning
* Parking spaces
* Preferred area
* Furnishing status

Target variable:

* Price

---

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the CSV dataset using Pandas.
2. Displayed the first 10 rows.
3. Checked dataset dimensions.
4. Identified missing values.
5. Removed duplicate rows.
6. Handled missing values.
7. Converted categorical variables using one-hot encoding.

---

## Machine Learning Models Used

### 1. Linear Regression

A basic regression algorithm used to predict house prices by finding linear relationships between features and price.

### 2. Random Forest Regressor

An ensemble learning algorithm that uses multiple decision trees for prediction.

---

## Model Evaluation Metrics

The models were evaluated using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* R² Score

---

## Visualizations Created

* House Price Distribution Histogram
* Correlation Heatmap
* Actual vs Predicted Price Scatter Plot

---

## Key Findings

* Area, number of bathrooms, and number of stories have the strongest impact on house prices.
* Houses with air conditioning and those located on the main road tend to have higher prices.
* Linear Regression performed better than Random Forest for this dataset.
* The dataset is relatively small, so a simpler model produced better results.

---

## Business Recommendation

Real estate businesses should pay close attention to house area, number of bathrooms, and number of stories while pricing properties.

To improve prediction accuracy in the future, additional features such as location, age of the house, nearby schools, hospitals, and public facilities can be included.

---


## Author

Tasneem Aslam Ansari
