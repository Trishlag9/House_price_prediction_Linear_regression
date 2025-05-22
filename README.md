# 🏡 House Price Prediction using Linear Regression

This project involves predicting house prices per unit area using real estate data and basic machine learning (Linear Regression). The objective is to analyze influential features and build a regression model that can reasonably predict house prices.

## 📁 Dataset Overview

- **Source**: Real estate dataset (CSV format)
- **Rows**: 414 records
- **Columns**:
  - `Transaction date`
  - `House age`
  - `Distance to the nearest MRT station`
  - `Number of convenience stores`
  - `Latitude`
  - `Longitude`
  - `House price of unit area` (target variable)

## 📊 Exploratory Data Analysis (EDA)

### ✅ Steps Performed

- **Checked Data Types** using `df.info()`
- **Statistical Summary** using `df.describe()`
- **Missing Value Check** using `df.isnull().sum()`
- **Visualizations:**
  - Histograms to explore distribution of features
  - Correlation matrix using `seaborn.heatmap`
  - Scatter plots to analyze relationship between features and target variable

### 🔍 Key Insights
- `Distance to MRT` and `No. of convenience stores` show moderate correlation with price
- Some features like `House age` have weaker relationships

## 🤖 Model Building

### 🔧 Model Used:
- **Linear Regression** from `sklearn.linear_model`

### 🧪 Steps:
1. Selected relevant features (e.g., `House age`, `Distance to MRT`, `Convenience stores`, `Latitude`, `Longitude`)
2. Split the data using `train_test_split()`
3. Trained a Linear Regression model
4. Made predictions on the test set
5. Evaluated model performance with:
   - **Residual Plot**
   - **Predicted vs Actual Plot**
   - **`r2_score`** (can be added if not present)

### 📈 Residual Plot:
- Showed how well predicted prices align with actual prices
- Helped detect any patterns or outliers in residuals

## 📌 Key Visuals Included

- 📉 Histograms of all numerical features
- 🧮 Correlation heatmap
- 🔍 Scatter plots showing feature vs house price
- 📐 Linear regression actual vs predicted chart

## 🚀 Future Enhancements

- Try more advanced regression models: **Ridge**, **Lasso**, **Random Forest**
- Perform **feature scaling** or **log transformation**
- Add **model evaluation metrics** like MAE, MSE, RMSE

## 🧠 Learning Highlights

- Strong hands-on with `pandas`, `matplotlib`, `seaborn`
- Built complete pipeline from loading data → EDA → model building → evaluation
- Learned how to interpret relationships using plots and statistics

## 🏷️ Tags

`#Python` `#LinearRegression` `#MachineLearning` `#EDA` `#RealEstateAnalytics` `#JupyterNotebook`

