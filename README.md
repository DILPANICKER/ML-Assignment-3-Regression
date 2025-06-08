# ML-Assignment-3-Regression
# California Housing Price Prediction - Regression Analysis

## Overview
This project compares five regression algorithms on the California Housing dataset to predict median house values. Implemented in Python using scikit-learn, it covers:
- Data preprocessing and feature scaling
- Model implementation (Linear Regression, Decision Tree, Random Forest, Gradient Boosting, SVR)
- Performance evaluation (MSE, MAE, R²)

## Key Findings
- **Best Model**: Random Forest Regressor (R² = 0.787)
- **Worst Model**: Linear Regression (R² = 0.576)
- **Insight**: Tree-based models outperform linear models due to non-linear relationships in housing data

## Files
- `California_Housing_Regression.ipynb`: Complete Jupyter Notebook with analysis
- `README.md`: This overview

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## Usage
1. Clone repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run Jupyter Notebook

## Results Preview
![Model Comparison](results_plot.png)
