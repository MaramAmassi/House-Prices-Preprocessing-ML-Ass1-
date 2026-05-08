# House Prices - Advanced Regression Preprocessing

## Project Overview
This project focuses on the **Data Preprocessing** and **Exploratory Data Analysis (EDA)** phases for the Kaggle House Prices dataset. The goal is to clean raw data, engineer new features, and build a reusable pipeline for machine learning modeling.

## Key Features
- **Memory Optimization**: Downcasting numeric types and converting objects to categories.
- **In-depth EDA**: Missing value logic (0/1 analysis), outlier detection, and neighborhood price trends.
- **Advanced Cleaning**: Handling outliers, log transformations for target skewness, and median imputation.
- **Feature Engineering**: Creating `TotalSF`, temporal analysis (converting years to age), and hybrid encoding (Ordinal Manual Mapping & One-Hot Encoding).
- **Reusable Pipeline**: A Scikit-Learn pipeline for consistent scaling and final imputation.

## How to Run
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Open `House_Price_Analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to see the results and the final processed data matrix.

## Technologies Used
- Python, Pandas, Numpy
- Seaborn, Matplotlib, Plotly (Visualization)
- Scikit-Learn (Pipeline & Scaling)
