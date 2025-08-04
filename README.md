# 🧠 Student Mental Health & Performance — Data Cleaning & Preprocessing

This project demonstrates how to clean and preprocess raw student data to prepare it for Machine Learning (ML) tasks. The dataset includes features related to mental health, study habits, and academic performance, with realistic patterns and some noise to simulate real-world data.

---

## 📁 Dataset Overview

**Filename:** `student_mental_health.csv`  
**Records:** 50  
**Columns:**

- `Name`: Student identifier (string)
- `Age`: Age of the student (integer)
- `Gender`: Male or Female (categorical)
- `Sleep_Hours`: Average sleep hours per day (float)
- `Study_Hours`: Daily study duration in hours (float)
- `Stress_Level`: Self-reported stress (Low, Medium, High)
- `Mental_Health_Score`: Score from a mental health assessment (0–100)
- `Grades`: Academic performance score (0–100)

---

## 🧹 Data Cleaning & Preprocessing Steps

### 1. 📥 Import Libraries and Dataset
- Imported required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Loaded dataset and inspected basic info (data types, null values, shape)

### 2. 🧱 Handling Missing Values
- Used `mean` or `median` imputation for missing numeric values (e.g., Sleep_Hours)
- Used `mode` or forward fill (`ffill`) for categorical columns

### 3. 🔢 Encoding Categorical Variables
- Converted `Gender` and `Stress_Level` into numerical format using `pd.get_dummies()` for ML compatibility

### 4. ⚖️ Feature Scaling
- Applied `StandardScaler` (Z-score normalization) on numerical features like:
  - `Sleep_Hours`
  - `Study_Hours`
  - `Grades`

### 5. 📦 Outlier Detection & Removal
- Used **boxplots** (`seaborn`) to visually inspect outliers
- Removed outliers based on 1.5×IQR rule or domain knowledge

---

## 📊 Visualizations

- **Boxplots** for identifying outliers
- **Countplots** for gender/stress levels
- **Histograms** and **pairplots** to analyze distributions and relationships

---

## 💡 Key Learnings

- Handling missing values appropriately ensures data quality
- Encoding and scaling are essential for algorithms to perform correctly
- Outlier handling prevents bias in model training

---

## 🚀 Next Steps

- Apply machine learning models (e.g., Linear Regression, Decision Trees)
- Perform correlation analysis and feature selection
- Deploy as a mini mental health analysis dashboard

---

## 🛠️ Tools & Libraries Used

- Python 3
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (for scaling)

---

## 📌 Author

**Pooja V.**  
3rd Year BTech - AI & Data Science  
Chennai, India

---

## 📎 License

This project is for educational purposes only and uses mock data.
