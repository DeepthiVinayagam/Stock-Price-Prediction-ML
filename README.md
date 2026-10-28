# Stock Price Prediction Using Machine Learning

A machine learning project for analyzing stock-price trends and predicting short-term stock movement using regression, classification, time-series validation, and model explainability.

## Features

- Historical stock data collection using Yahoo Finance (`yfinance`)
- Technical indicator and feature engineering
- Regression models for price and return prediction
- Classification of stock movement (UP/DOWN)
- Walk-forward validation for more reliable evaluation
- Trading strategy backtesting
- SHAP-based model explainability
- Interactive stock prediction interface using Gradio

## Technology Stack

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Gradio
- Yahoo Finance

## Project Structure

```text
Stock-Price-Prediction-ML/
├── notebooks/
│   └── stock_prediction.ipynb
├── reports/
│   └── stock_prediction_implementation.pdf
├── requirements.txt
├── README.md
└── .gitignore
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/Stock-Price-Prediction-ML.git
cd Stock-Price-Prediction-ML
```

### 2. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Run the notebook

Start Jupyter:

```bash
jupyter notebook
```

Open `notebooks/stock_prediction.ipynb` and run the cells in order.

You can also upload the notebook to Google Colab and run it there.

## Evaluation

The notebook explores regression performance, classification accuracy, walk-forward validation, and backtested trading performance. Actual results depend on the data and execution environment; consult the notebook outputs for the measured results.

## Important Limitations

- Stock prices are uncertain and difficult to predict consistently.
- Historical performance does not guarantee future results.
- Backtests may differ from real trading because of execution costs and market conditions.
- Predictions are for educational and research purposes only, not financial advice.

## License

A license has not yet been selected for this project.
