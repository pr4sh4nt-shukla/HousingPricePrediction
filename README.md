# 🏠 Ames Housing Price Prediction
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)](https://scikit-learn.org/)
[![Analysis](https://img.shields.io/badge/Data-Regression%20Analysis-red)](https://en.wikipedia.org/wiki/Regression_analysis)

## 🎯 Project Goal
The objective of this project is to build a robust regression model to predict residential home prices in Ames, Iowa. Using a dataset with over 70 features, we analyze how physical attributes (like square footage) and subjective qualities (like material finish) influence market value.



---

## 🛠️ The Data Science Pipeline

### 1. Exploratory Data Analysis (EDA)
* **Outlier Detection:** Identified and handled extreme values in living area and sale price.
* **Correlation Mapping:** Visualized the strongest predictors of value, such as `OverallQual` and `GrLivArea`.
* **Missing Value Imputation:** Strategically filled gaps in features like `LotFrontage` and `GarageType`.

### 2. Feature Engineering
* **Categorical Encoding:** Transformed qualitative rankings (Excellent, Good, Fair) into numeric scales.
* **Skewness Correction:** Applied log transformations to skewed numeric variables to improve model normality.

### 3. Model Development & Evaluation
* **Algorithm:** Multiple Linear Regression.
* **Metrics:** Evaluated using **R² Score** (Variance explanation) and **RMSE** (Prediction error).

---

## 📂 Repository Structure
* `Housing_big_data_GitHub_Ready.ipynb` : The full analysis and modeling workflow.
* `ames iowa housing.csv` : The raw dataset containing 2,900+ observations.
* `requirements.txt` : List of Python packages required.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/housing-price-prediction.git](https://github.com/your-username/housing-price-prediction.git)
