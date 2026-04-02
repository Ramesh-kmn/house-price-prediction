# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict house prices using Machine Learning techniques. The objective is to analyze key features influencing house prices and build a predictive model.

## 📂 Dataset

* Source: Kaggle House Prices Dataset
* The dataset contains various features such as house size, quality, location, and other attributes.

## 📊 Exploratory Data Analysis (EDA)

* Analyzed distribution of `SalePrice`
* Identified correlations between features
* Visualized relationships using scatter plots and heatmaps

## 🔍 Key Insights

* `OverallQual` has a strong impact on house price
* `GrLivArea` is highly correlated with `SalePrice`
* Larger houses tend to have higher prices
* Outliers were observed in houses with large living areas
* Important features: `OverallQual`, `GrLivArea`, `GarageCars`

## 🤖 Model Building

* Model used: Random Forest Regressor
* Handled missing values using mean/mode
* Applied one-hot encoding for categorical variables
* Split data into training and testing sets
* Evaluation metrics: RMSE and R² Score

## 📈 Results

* The model achieved an R² score of (add your value here)
* RMSE: (add your value here)
* The model successfully identified key factors influencing house prices

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Run the Jupyter Notebook

## 📁 Project Structure

* House_Price_Project.ipynb
* house_prices.csv

## 🔮 Future Improvements

* Hyperparameter tuning
* Try advanced models like XGBoost
* Improve feature engineering

## 👤 Author

Ramesh Kukkamudi
GitHub: https://github.com/Ramesh-kmn
