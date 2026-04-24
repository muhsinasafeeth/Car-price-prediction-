# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project models car prices using multiple machine learning algorithms.  
The dataset contains specifications of cars (engine size, horsepower, fuel type, body style, etc.) and their prices.  
The goal is to identify significant variables affecting car prices and build predictive models to assist a Chinese automobile company entering the US market.

---

## 📂 Dataset
- **File**: `CarPrice_Assignment.csv`
- **Rows**: 205
- **Columns**: 26 (mix of categorical and numerical features)
- **Target Variable**: `price`

---

## 🛠️ Steps Covered
### 1. Data Loading & Preprocessing
- Checked missing values and data types  
- Encoded categorical variables  
- Standardized numerical features  
- Applied log transformation to `price` to reduce skewness  

### 2. Exploratory Data Analysis (EDA)
- Distribution plots for price  
- Correlation heatmap  
- Boxplots for categorical variables vs price  
- Scatter plots for numerical features vs price  
- Pairplot for key predictors  

### 3. Model Implementation
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor (SVR)  

### 4. Model Evaluation
- Metrics: R², Mean Squared Error (MSE), Mean Absolute Error (MAE)  
- Compared performance across models  
- Evaluated both original and log-transformed targets  

### 5. Feature Importance
- Identified top predictors: `enginesize`, `horsepower`, `curbweight`, `carwidth`  

### 6. Hyperparameter Tuning
- GridSearchCV for Random Forest & Gradient Boosting  
- Improved performance with optimized parameters  

---

## 📊 Results
- **Best Models**: Random Forest & Gradient Boosting  
- **Key Insights**:  
  - Cars with higher engine size, horsepower, and curb weight are priced higher  
  - RWD and turbo aspiration cars command premium prices  
  - Log transformation improved performance for linear models  

---

## 📁 Project Structure
CarPrice_Project/

│── data/

│   └── CarPrice_Assignment.csv

│── notebooks/

│   └── CarPrice_Prediction.ipynb

│── plots/

│   └── eda_visualizations.png

│── README.md


