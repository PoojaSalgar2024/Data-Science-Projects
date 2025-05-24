# 🏠 California Housing Price Prediction

This project aims to predict median house prices in California using machine learning models such as Linear Regression and Random Forest. The dataset is sourced from the `sklearn.datasets.fetch_california_housing()` function, which includes data collected from the 1990 U.S. Census.

---

## 📊 Dataset Overview

- 📍 **Source**: Scikit-learn's California Housing Dataset
- 🧮 **Features (8 total)**:
  - `MedInc` – Median income in block group
  - `HouseAge` – Median house age
  - `AveRooms` – Average number of rooms per household
  - `AveBedrms` – Average number of bedrooms per household
  - `Population` – Block group population
  - `AveOccup` – Average household occupancy
  - `Latitude` and `Longitude` – Geographic location
- 🎯 **Target**: Median house value (in $100,000s)

---

## 🔧 Tools & Technologies Used

- Python 3
- Jupyter Notebook
- Libraries: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`

---

## 📈 Models Applied

| Model              | Description                           |
|-------------------|---------------------------------------|
| Linear Regression | Baseline regression model             |
| Random Forest     | Ensemble model for better accuracy    |

---

## 📊 Model Evaluation

| Model              | R² Score | RMSE     | MAE     |
|-------------------|----------|----------|---------|
| Linear Regression | ~0.61    | ~0.74    | ~0.56   |
| Random Forest     | ~0.82    | ~0.49    | ~0.36   |

---

## 📉 Visualizations

### 🔹 Correlation Heatmap
Shows relationships between features and helps identify highly correlated variables.

![Correlation Heatmap](../images/correlation_heatmap.png)

### 🔹 Actual vs Predicted
Scatter plot comparing true vs predicted house values for each model.

![Actual vs Predicted](../images/actual_vs_predicted.png)

---

## 🧠 Key Learnings

- Feature scaling significantly impacts model performance (especially for linear models).
- Random Forest provided better accuracy due to its ability to model non-linear patterns.
- Evaluating models with R², RMSE, and MAE helps compare their real-world performance.

---

## 🚀 How to Run

1. Clone the repository or download the folder.
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
