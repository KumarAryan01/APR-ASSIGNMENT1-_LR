# APR-ASSIGNMENT1-_LR

# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview
This project analyzes housing data to predict house prices using a **Linear Regression model**.  
The dataset (`data.csv`) contains information about various house features and their corresponding prices.

---

## 📂 Dataset
- **File Used:** `data.csv`  
- **Features:** House attributes such as `sqft_living`, `bedrooms`, etc.  
- **Target Variable:** `price`  
- **Dropped Columns:** `date`, `street`, `city`, `statezip`, `country` (irrelevant for prediction)

---

## 🔎 Analysis Steps

### 1. Data Loading & Exploration
- Loaded dataset into a Pandas DataFrame.  
- Checked for missing values → None found.  
- Reviewed data types and initial records.  

### 2. Data Preprocessing
- Removed irrelevant columns (`date`, `street`, `city`, `statezip`, `country`).  
- Separated features (`X`) and target variable (`y`).  

### 3. Data Splitting
- Split data into **training (80%)** and **testing (20%)** sets.  

### 4. Model Building & Training
- Used **Linear Regression** from `scikit-learn`.  
- Trained the model on the training set.  

### 5. Model Evaluation
- **Mean Squared Error (MSE):** `986,921,767,056.10`  
- **R-squared (R²):** `0.0323`  

### 6. Visualization
- Scatter plot of **sqft_living vs. price**.  
- Scatter plot of **actual vs. predicted prices**.  

---

## 📊 Findings
- The **Linear Regression model performed poorly**:
  - R² score (`0.0323`) indicates it explains only ~3% of the variance in house prices.  
  - Scatter plot shows predictions are not well-aligned with actual values.  

---

## ✅ Conclusion
- Simple Linear Regression is **not sufficient** for predicting house prices in this dataset.  

---

## 🚀 Next Steps
- Try more advanced models:
  - Polynomial Regression  
  - Decision Trees  
  - Random Forests  
- Perform **feature engineering** (create/transform features).  
- Handle **outliers** and potential **data inconsistencies**.  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib / Seaborn  

---

## 📌 Author
👤 **Kumar Aryan**  
📧 [kumararyan86039@gmail.com](mailto:kumararyan86039@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/kumar-aryan-436ba61b7/) | [GitHub](https://github.com/KumarAryan01)


