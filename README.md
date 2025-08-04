# -Task1__DataPreprocessing
Titanic dataset preprocessing for AI &amp; ML internship task — includes data cleaning, handling null values, encoding categorical features, feature scaling, and outlier removal using Python and Pandas.
# Task 1: Data Cleaning & Preprocessing

## 🔍 Objective
To clean and prepare the Titanic dataset for Machine Learning by performing data cleaning, handling null values, encoding categorical features, feature scaling, and removing outliers.

---

## 📁 Dataset
- Source: [Titanic Dataset from Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-Dataset.xlsx`

---

## 🛠 Tools & Libraries
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🧠 What You'll Learn
- How to clean and explore raw datasets
- How to handle missing values using mean/median/mode
- How to convert categorical data using one-hot encoding
- How to scale numerical features using StandardScaler
- How to detect and remove outliers using boxplots

---

## 🔄 Steps Performed

1. **Import the dataset**
   - Used Pandas to load the Excel file into a DataFrame

2. **Explore dataset**
   - Checked data types and missing values using `info()` and `isnull().sum()`

3. **Handle missing values**
   - Filled missing values in `Age` using median
   - Filled missing `Embarked` values using mode
   - Dropped the `Cabin` column due to too many missing entries

4. **Convert categorical data**
   - Applied one-hot encoding to `Sex` and `Embarked` columns

5. **Feature scaling**
   - Used `StandardScaler` to normalize `Age` and `Fare` columns

6. **Outlier detection and removal**
   - Visualized `Fare` outliers using a boxplot
   - Removed top 1% extreme fare values

---

## 📂 Output Files
- `cleaned_titanic.csv` – Cleaned dataset ready for ML
- `titanic_preprocessing.py` – Script containing all code
- `Titanic-Dataset.xlsx` – Original dataset used

---

## ✅ Result
Successfully cleaned and preprocessed Titanic dataset, ready for use in training ML models.

---

## 🔗 Submission
This repository is part of Task 1 for the AI & ML Internship program.
