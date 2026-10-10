# Retail Sales Data — Exploratory Data Analysis (EDA)

## Project objective
Analyze retail sales transactions to identify sales trends, customer demographic patterns, and product/category performance, then translate findings into actionable business recommendations.

## Tools
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab
- GitHub

## Repository structure
```text
retail-sales-eda/
├── data/
│   └── retail_sales.csv
├── notebooks/
│   └── retail_sales_eda.ipynb
└── README.md
```

## Dataset
Download a suitable retail sales CSV from Kaggle and save it as `data/retail_sales.csv`. One commonly used dataset contains transaction date, customer gender and age, product category, quantity, unit price, and total amount.

Dataset source example: https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

## Analysis performed
1. Dataset shape, data types, missing values, and duplicate checks
2. Descriptive statistics for numeric fields
3. Monthly and quarterly revenue trends
4. Customer age-group and gender analysis
5. Top 10 products if individual product names exist; otherwise category-level revenue analysis
6. Correlation heatmap for numeric variables
7. Additional transaction-value distribution visualization
8. Business recommendations based on the actual outputs

## How to run
1. Download the CSV dataset from Kaggle.
2. Put it in the `data/` folder and name it `retail_sales.csv`.
3. Open `notebooks/retail_sales_eda.ipynb` in Jupyter Notebook, or upload it to Google Colab.
4. Run all cells from top to bottom.
5. Review the charts and replace the bracketed prompts in the conclusion with findings from your results.

## Important note
Do not report example findings as if they came from your analysis. Recommendations should be based on the generated charts and tables. Revenue is not profit; check margins and costs before making inventory or pricing decisions.
