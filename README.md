# Sales Prediction Using Python

Oasis Infobyte Internship (OIBSIP) | Data Science | Task 5

## Objective
Build a regression model that predicts product sales from advertising spend on TV, Radio and Newspaper, and find out which channel has the highest impact on sales.

## Dataset
Classic `Advertising.csv` dataset (Kaggle), included in this repo. It has 200 rows with TV, Radio, Newspaper spend and Sales, with no missing values.

## Steps Performed
1. Loaded the data and checked shape, data types, null values, duplicates and descriptive statistics
2. EDA: pairplot, scatter plots of Sales vs TV / Radio / Newspaper, correlation heatmap
3. 80/20 train/test split
4. Trained Linear Regression (baseline), Polynomial Regression (degree 2) and Random Forest Regressor
5. Evaluated with MAE, RMSE and R² score
6. Residual plots to check whether the errors are random or systematic
7. Interpreted channel impact using regression coefficients and Random Forest feature importance
8. Predicted sales for new example budgets

## Tools Used
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## Outcome
**Polynomial Regression (degree 2)** was the best model with **R² = 0.987, MAE = 0.53 and RMSE = 0.64**. The baseline Linear Regression reached R² = 0.899 and Random Forest reached R² = 0.982. **TV** has the biggest impact on sales, followed by **Radio**, while **Newspaper** has almost no effect.

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Sales_Prediction.ipynb
```

## Demo Video
<YouTube/LinkedIn link>
