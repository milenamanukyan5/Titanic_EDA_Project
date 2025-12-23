# Titanic EDA and Feature Engineering

## Project Title
Titanic EDA and Feature Engineering

## Goal
The main goal of this project is to analyze the Titanic passengers' data to identify patterns and factors that influenced survival rates. We performed data cleaning, exploratory data analysis (EDA), and feature engineering to prepare the data for machine learning models.

## Technologies Used
* **Python**
* **Pandas** (for data manipulation)
* **Seaborn & Matplotlib** (for visualization)

## Key Findings & Conclusions
Based on the analysis, we found the following:

1.  **Gender:** Females had a significantly higher survival rate (~74%) compared to males (~18%).
2.  **Class (Social Status):** Passengers in 1st class had the highest survival chance, while 3rd class passengers had the lowest.
3.  **Family Size:** Passengers traveling alone or with very large families had lower survival rates compared to those with small families (2-4 members).
4.  **Fare:** There is a positive correlation between Fare and Survival; higher fares are linked to better survival chances.
5.  **Title Extraction:** We successfully extracted titles (Mr, Mrs, Miss, Master) from names, which proved to be a strong predictor of survival (e.g., 'Mr' has a very low survival rate).

## Visualizations
Check the `.ipynb` file to see the heatmaps and bar charts representing these findings.
