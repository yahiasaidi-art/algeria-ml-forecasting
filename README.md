# algeria-ml-forecasting
Machine Learning for Economic Forecasting in Algeria
# Machine Learning for Economic Forecasting in Algeria

This repository supports the research paper:  
**"Machine Learning-Based Economic Forecasting in Resource-Constrained Economies: A Case Study of Algeria"**

## 📄 Overview
This study evaluates five machine learning models — Linear Regression, ARIMA, Random Forest, Prophet, and LSTM — for forecasting key macroeconomic indicators in Algeria:
- GDP Growth
- Inflation
- Unemployment

Models are trained on 2003–2019 data and evaluated on out-of-sample forecasts (2020–2023), demonstrating that ML reduces forecasting errors by 25–40% compared to traditional methods.

## 📂 Files
- `algeria_forecasting.ipynb`: Full Jupyter notebook with code, models, and evaluation
- `data.csv`: Cleaned dataset (2003–2023) used in the analysis

## 🚀 How to Use
1. Download the notebook and open in:
   - [Google Colab](https://colab.research.google.com) (recommended)
   - Jupyter Notebook
   - VS Code
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn prophet tensorflow matplotlib seaborn statsmodels
