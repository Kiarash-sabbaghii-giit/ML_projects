🏡 California Housing Price Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.13-blue)![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)![License](https://img.shields.io/badge/License-MIT-green)

📌 Project Overview

This project develops a Linear Regression model to predict California housing prices based on demographic and geographical features.

The project covers the complete machine learning workflow, from data exploration and preprocessing to model evaluation and feature importance analysis.

---

🎯 Goal

Build an interpretable regression model capable of accurately estimating house prices while analyzing the contribution of each feature.

---

📊 Dataset

Feature| Description
longitude| Geographic longitude
latitude| Geographic latitude
housing_median_age| Median house age
total_rooms| Total rooms
total_bedrooms| Total bedrooms
population| Population
households| Number of households
median_income| Median income
ocean_proximity| Distance from ocean (categorical)
Target| Median House Value

---

🔄 Machine Learning Pipeline

1. Data Loading

- Import dataset
- Inspect missing values
- Explore data types

---

2. Data Cleaning

- Handle missing values
- Remove inconsistencies
- Detect outliers (if necessary)

---

3. Exploratory Data Analysis (EDA)

- Distribution plots
- Correlation matrix
- Feature relationships
- Target distribution

---

4. Preprocessing

- One-Hot Encoding
- Feature Scaling
- Train/Test Split

---

5. Model Training

- Linear Regression

---

6. Model Evaluation

The following metrics were calculated:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

📈 Feature Importance

Feature importance was analyzed using the absolute values of the Linear Regression coefficients.

Example ranking:

Rank| Feature
1| Median Income
2| Latitude
3| Longitude
4| Housing Median Age
5| Total Rooms

---

🧪 Experiment

Two experiments were conducted.

Experiment 1

Entire dataset

Experiment 2

Random sample of 10,000 observations

---

📊 Results Comparison


«Replace the values above with your experimental results.»

---

💻 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---


---

▶️ Run

jupyter notebook

Run the notebook from top to bottom.

---

---

🔮 Future Improvements

- Ridge Regression
- Lasso Regression
- Elastic Net
- Random Forest Regressor
- XGBoost Regressor
- Hyperparameter tuning with GridSearchCV
- Cross-validation

---

👨‍💻 Author

Kiarash

---

📄 License

Licensed under the MIT License.
