# 📊 Assignment 06 - First ML Model & Evaluation

This repository contains my submission for **Assignment 06** of the **Full Stack AI/ML Engineering Bootcamp**.

The project demonstrates a complete **End-to-End Machine Learning Workflow**, starting from data cleaning and exploratory data analysis (EDA) to feature engineering, model training, evaluation, comparison, and final analysis.

---

## 📁 Dataset

**Dataset:** `student_dataset_dirty.csv`

The dataset contains student academic and demographic information, including:

- Student ID
- Age
- Gender
- City
- Class
- Attendance Percentage
- Study Hours per Day
- Math Score
- Science Score
- English Score
- Total Score
- Parent Education
- Internet Access
- Result (Pass/Fail)

---

## 🚀 Project Workflow

### 1. Data Analysis
- Loaded dataset
- Checked dataset shape
- Inspected column names and data types
- Checked missing values
- Removed duplicate records
- Generated descriptive statistics

---

### 2. Data Cleaning
- Fixed incorrect data types
- Corrected invalid values
- Standardized categorical labels
- Handled missing values using:
  - Median Imputation (Numerical Features)
  - Mode Imputation (Categorical Features)
- Removed duplicate Student IDs

---

### 3. Exploratory Data Analysis (EDA)

Performed:

- Histogram
- Boxplot
- Count Plot
- Correlation Heatmap
- Feature Distribution Analysis
- Relationship between Features and Target Variable

Also identified outliers and discussed whether they should be removed or retained.

---

### 4. Feature Engineering

Performed:

- Created new features:
  - Average Score
  - Study Efficiency
  - Attendance Category
- Label Encoding
- One-Hot Encoding
- Feature Scaling using StandardScaler
- Removed unnecessary columns

---

### 5. Train-Test Split

- Train-Test Ratio: **80 : 20**
- Used **Stratified Split** for the classification task to preserve class distribution.

---

## 🤖 Machine Learning Models

### 📈 Linear Regression

Target:
- **Total Score** (Continuous)

Evaluation Metrics:

- MAE
- MSE
- RMSE
- R² Score

---

### 📉 Logistic Regression

Target:
- **Result (Pass/Fail)**

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve

---

## 📊 Model Comparison

Both models were compared using their respective evaluation metrics in a comparison table for better interpretation.

---

## 📌 Final Analysis

The notebook includes:

- Model Performance Comparison
- Overfitting / Underfitting Discussion
- Learning Curve Analysis
- Final Conclusion
- Real-world Applications

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Kaggle Notebook
- GitHub

---

## 📂 Repository Structure

```
├── Assignment_06.ipynb
├── student_dataset_dirty.csv
├── README.md
```

---

## 📈 Learning Outcomes

Through this project, I learned how to:

- Clean real-world datasets
- Perform exploratory data analysis
- Engineer useful features
- Train Regression and Classification models
- Evaluate models using appropriate metrics
- Compare multiple machine learning models
- Interpret model performance
- Build an end-to-end machine learning pipeline

---

## 👨‍💻 Author

**Sayem Shuvo**

Full Stack AI/ML Engineering Bootcamp  
Shahjalal University of Science and Technology (SUST)

---

⭐ If you found this project useful, feel free to star the repository.
