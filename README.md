# 🚢 Task-02: Exploratory Data Analysis (EDA) - Titanic Dataset

This repository contains the solution for **Task-02** of the **Prodigy InfoTech Data Science Internship**, where I performed **data cleaning** and **exploratory data analysis (EDA)** on the **Titanic dataset**.

---

## 📌 Objective

- Perform data cleaning (handle missing values, drop unnecessary columns, encode categorical variables).
- Conduct exploratory data analysis (EDA) to uncover patterns, trends, and relationships in the data.
- Visualize insights using Python libraries like Matplotlib and Seaborn.

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning Performed

- Filled missing `Age` values with median.
- Dropped the `Cabin` column due to excessive missing values.
- Filled missing `Embarked` values with the mode.
- Encoded `Sex` and `Embarked` categorical columns into numeric format.
- Dropped irrelevant columns like `Name`, `Ticket`, and `PassengerId`.

---

## 📊 EDA Highlights

### 🔍 Univariate Analysis
- Countplot for `Survived`, `Pclass`, `Sex`
- Histogram for `Age` and `Fare`

### 🔍 Bivariate Analysis
- Survival rate based on gender and passenger class
- Fare vs Age scatter plot colored by survival

---

## 📌 Key Insights

- 🚺 Female passengers had a significantly higher survival rate.
- 🎟️ First-class passengers had the best survival rate.
- 👶 Children and younger passengers were more likely to survive.
- 💰 Higher fares were correlated with higher survival chances.

---

