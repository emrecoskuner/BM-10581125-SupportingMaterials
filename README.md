**UNIVERSITY OF MANCHESTER**

This reposiotry contains the code and the resources for MSc Data Science extended research project: 
“Time Series Prediction of Stock Returns Using Machine Learning Models: Study on Dow Jones Industrial Average Stocks (2000–2024)”

**DATA**
- Source: Yahoo Finance (2000–2024) – daily historical data for DJIA 30 companies.
- Target Variable: t+1 monthly return.
- Technical Indicators: Momentum, MA20, MA50, RSI, Volatility.

**ENVIRONMENT**
- Python 3.9.23
- Jupyter Notebook
- Google Collaboratory for Data Extraction
- pandas, numpy, scikit-learn, xgboost, tensorflow/keras, statsmodels, matplotlib, seaborn
- See requirements.txt for library versions.

**MODELS IMPLEMENTED**
- Machine Learning: Random Forest, XGBoost, Support Vector Regression (SVR)
- Deep Learning: LSTM

**EVALUATION METRICS**
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Directional Accuracy (DA)

**RESULTS**
- LSTM was sensitive to highly volatile stocks (e.g., NVDA) and showed unstable performance.
- Tree-based methods (RF, XGBoost) performed robustly across medium/low volatility stocks.
- SVR showed weaker performance in highly volatile sectors (e.g., BA).
- Model performance and selection vary across different stocks, no superior model for all stocks.


Clone repository:
```bash
git clone https://github.com/emrecoskuner/BM-10581125-SupportingMaterials.git
cd BM-10581125-SupportingMaterials
``` 

Install dependencies: 
```bash
pip install -r requirements.txt
``` 

**LICENCE**
This repository is for academic purposes only (MSc Data Science – University of Manchester).
Please cite appropriately if used.
