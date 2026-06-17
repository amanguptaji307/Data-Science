# House Price Prediction Model Comparison using Machine Learning

## Project Overview
This project focuses on predicting house prices using various Machine Learning regression algorithms and comparing their performance to identify the most accurate model.

The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation. Multiple regression models were trained on the same housing dataset and compared using standard performance metrics such as Mean Absolute Error (MAE).

The primary objective was not only to predict house prices but also to determine which machine learning algorithm performs best for the given dataset. By analyzing and comparing the results of different models, the project provides insights into model selection and performance optimization for real-world housing price prediction problems.

## Objective
- Perform data preprocessing and exploratory data analysis (EDA).
- Handle missing values and feature engineering.
- Train and evaluate machine learning regression models.
- Which model is best for predicting house prices?

## Dataset
The dataset contains housing-related features such as:
## 📊 Dataset Features

| Feature | Description |
|----------|-------------|
| Id | Unique identifier for each property |
| MSSubClass | Building class/type of dwelling |
| MSZoning | Zoning classification of the property |
| LotArea | Size of the lot in square feet |
| LotConfig | Lot configuration and layout |
| BldgType | Type of residential building |
| OverallCond | Overall condition rating of the house |
| YearBuilt | Year the house was originally built |
| YearRemodAdd | Year of last remodeling or renovation |
| Exterior1st | Primary exterior material of the house |
| BsmtFinSF2 | Finished basement area (Type 2) in square feet |
| TotalBsmtSF | Total basement area in square feet |
| SalePrice | Selling price of the house (Target Variable) |

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Preprocessing
- Loaded and inspected the dataset.
- Handled missing values.
- Encoded categorical features.
- Performed feature scaling where required.

### 2. Exploratory Data Analysis (EDA)
- Analyzed feature distributions.
- Visualized correlations between variables.
- Identified important factors affecting house prices.

### 3. Model Building
Implemented machine learning regression models:
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- K-Nearest Neighbors (KNN) Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor

### 4. Model Evaluation
Performance metrics used:
- Mean Absolute Error (MAE)

### 5. Models Compared

To identify the most accurate house price prediction model, multiple regression algorithms were trained and evaluated on the same dataset.

The following models were compared:

1. **Support Vector Regressor (SVR)**
   - Uses support vectors to perform regression.
   - Effective for capturing non-linear relationships.

2. **Linear Regression**
   - A baseline regression model that assumes a linear relationship between features and target values.
   - Simple, interpretable, and computationally efficient.

3. **K-Nearest Neighbors (KNN) Regressor**
   - Predicts house prices based on the average prices of similar neighboring houses.
   - Sensitive to feature scaling and dataset size.

4. **Gradient Boosting Regressor**
   - An ensemble learning technique that combines multiple weak learners to improve prediction accuracy.
   - Effective at handling complex patterns in housing data.

5. **Decision Tree Regressor**
   - Creates a tree-based structure to make predictions.
   - Easy to interpret but can be prone to overfitting.

6. **Random Forest Regressor**
   - An ensemble of multiple decision trees.
   - Reduces overfitting and improves generalization performance.
## Result: Model Performance

The models were evaluated using **Mean Absolute Percentage Error (MAPE)**, where a lower value indicates better prediction accuracy.

| Model | MAPE |
|---------|---------|
| Random Forest | 0.074 |
| Gradient Boosting | 0.087 |
| Decision Tree | 0.120 |
| KNN | 0.133 |
| SVR | 0.177 |
| Linear Regression | 0.185 |

### 🏆 Best Performing Model

**Random Forest Regressor** achieved the lowest Mean Absolute Percentage Error (MAPE) of approximately **7.4%**, making it the most accurate model for predicting house prices in this project.

### Key Findings

- Random Forest provided the highest prediction accuracy.
- Gradient Boosting was the second-best performing model.
- Linear Regression showed the highest prediction error, indicating that the relationship between housing features and prices is not purely linear.
- Ensemble methods (Random Forest and Gradient Boosting) significantly outperformed traditional regression techniques.
## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/amanguptaji307/house-price-prediction.git
