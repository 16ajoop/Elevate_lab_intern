# 📈 Task 3: Linear Regression

This project demonstrates the implementation of **Simple** and **Multiple Linear Regression** using the **Auto MPG dataset**.  

---

## 🎯 Objective
- Understand how linear regression works
- Implement simple and multiple regression with **scikit-learn**
- Evaluate model performance using error metrics
- Visualize regression line and interpret coefficients  

---

## 🛠️ Tools & Libraries
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📂 Dataset
**Auto MPG Dataset**  
- **Target variable (y):** `mpg` (miles per gallon)  
- **Features (X):** `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model year`, `origin`  

---

## 🚀 Steps
1. **Import and preprocess data**  
   - Handle missing values (`horsepower`)  
   - Drop irrelevant column (`car name`)  

2. **Split data**  
   - Train-test split (80–20)  

3. **Simple Linear Regression**  
   - Predict `mpg` using only `weight`  
   - Visualize regression line  

4. **Multiple Linear Regression**  
   - Use all features to predict `mpg`  
   - Analyze coefficients  

5. **Evaluate Model**  
   - Metrics: MAE, MSE, R²  


## 📈 Metrics (Sample Output)
- **Simple Regression:**  
  - MAE: 3.5  
  - MSE: 20.2  
  - R²: 0.71  

- **Multiple Regression:**  
  - MAE: 2.1  
  - MSE: 9.8  
  - R²: 0.85  

---

## ✅ Key Takeaways
- Vehicle **weight** has a strong negative correlation with mpg  
- Newer model years generally improve fuel efficiency  
- Multiple regression gives better performance than simple regression  

---
