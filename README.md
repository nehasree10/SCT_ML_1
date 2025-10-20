# 🏡 House Price Prediction using Linear Regression

## 📘 Overview
This project implements a **Linear Regression** model to predict house prices based on various features such as living area, basement size, quality, year built, and neighborhood.  
It demonstrates **data preprocessing**, **feature engineering**, **model training**, **evaluation**, and **visualization** using **Scikit-learn** pipelines.

---

## 🧠 Key Features
- Data preprocessing with handling of missing values  
- Encoding of categorical variables using OneHotEncoder  
- Feature scaling using StandardScaler  
- Linear Regression model training and evaluation  
- Cross-validation for model robustness  
- Visualization of Actual vs Predicted Prices  
- Display of top influential features based on model coefficients  

---

## 🧩 Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Google Colab  

---

## 📂 Dataset
This project uses the **House Prices dataset (`train.csv`)** from Kaggle’s competition  
[House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)

**Features used in this project:**
- `GrLivArea` — Above-ground living area (sq. ft.)  
- `TotalBsmtSF` — Total basement area  
- `OverallQual` — Overall material and finish quality  
- `YearBuilt` — Year the house was built  
- `FullBath` — Number of full bathrooms  
- `BedroomAbvGr` — Number of bedrooms above ground  
- `TotRmsAbvGrd` — Total rooms above ground  
- `Neighborhood` — Physical location  

**Target variable:**  
- `SalePrice` — The property's sale price  

---

## ⚙️ How to Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/house-price-prediction.git
cd house-price-prediction
# SCT_ML_1
