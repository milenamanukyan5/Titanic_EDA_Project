# 🚢 Titanic Survival Analysis: EDA & Feature Engineering

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Library](https://img.shields.io/badge/Library-Pandas%20%7C%20Seaborn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project is part of a university assignment to analyze the famous **Titanic dataset**. The main objective is to perform Exploratory Data Analysis (EDA), clean the data, and engineer new features to understand the factors affecting passenger survival rates.

## 📂 Dataset
The data is obtained from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data).
* **Train Data:** Used for analysis and pattern recognition (contains `Survived` column).

## 🛠️ Key Techniques Applied

### 1. Data Cleaning
* **Handling Missing Values:**
    * `Age`: Imputed based on **Pclass** averages (wealthier passengers tended to be older).
    * `Embarked`: Filled with the mode ('S').
    * `Cabin`: Dropped due to >77% missing data.
* **Data Type Conversion:** Converted categorical variables into numeric formats for analysis.

### 2. Feature Engineering
* **Title Extraction:** Extracted titles (Mr, Mrs, Miss, Master) from names to categorize social status. Grouped rare titles (e.g., *the Countess*, *Col*, *Dr*) into an 'Other' category.
* **Family Size:** Created a new feature combining `SibSp` and `Parch` to analyze family survival patterns.
* **IsAlone:** Created a binary feature to identify passengers traveling solo.

### 3. Exploratory Data Analysis (EDA)
* **Visualizations:** Used Heatmaps, Bar Plots, and Count Plots to visualize correlations.
* **Correlation Matrix:** Analyzed the linear relationship between features and survival.

## 📊 Key Findings
Based on the analysis, the following patterns were identified:
1.  **Women First:** Female passengers had a ~74% survival rate, while males had only ~18%.
2.  **Socio-Economic Status:** 1st Class passengers had significantly higher survival chances than 3rd Class.
3.  **Family Factor:** Small families (2-4 members) had better survival rates than those alone or with large families.
4.  **Titles Matter:** The title 'Mr' has a strong negative correlation with survival, while 'Mrs' and 'Miss' correlate positively.

## 🚀 How to Run
1.  Clone the repository.
2.  Open `Titanic_EDA_Project.ipynb` in Jupyter Notebook or Google Colab.
3.  Ensure `train.csv` is in the same directory.
4.  Run all cells to see the analysis and visualizations.
