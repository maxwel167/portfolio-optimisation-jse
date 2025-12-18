# Portfolio Optimisation and Risk Analysis of JSE Equities

## 📊 Project Overview
A quantitative finance project analyzing 6 JSE-listed stocks using Modern Portfolio Theory to construct optimal portfolios and calculate risk metrics.

## 🎯 Key Results
- **Optimal Portfolio**: 80.74% Naspers (NPN.JO), 19.26% Anglo American (AGL.JO)
- **Annual Return**: 11.72% (optimal) vs 3.48% (equal-weighted)
- **Risk Measures**: 95% Daily VaR: -3.56%, CVaR: -5.31%

## 🛠️ Technologies
- Python, pandas, NumPy, yfinance
- Modern Portfolio Theory
- Risk metrics (VaR, CVaR, Sharpe ratio)

## 📁 Files
- `portfolio_optimisation_jse.ipynb` - Main analysis notebook
- `images/` - Generated visualizations

## 🚀 How to Run
1. Clone repository: `git clone https://github.com/maxwel167/portfolio-optimisation-jse.git`
2. Install requirements: `pip install -r requirements.txt`
3. Open notebook: `jupyter notebook portfolio_optimisation_jse.ipynb`

## 📈 Visualizations

### 1. Normalized Price Trends
![Normalized Price Trends](images/price_trends.png)
*Price movements of all 6 JSE stocks normalized to start at 1 (2019-2024)*

### 2. Returns Distribution Analysis
![Returns Distribution](images/returns_distribution.png)
*Histograms of daily returns for each stock with normal distribution overlay*

### 3. Correlation Heatmap
![Correlation Matrix](images/correlation_matrix.png)
*Heatmap showing correlation coefficients between different JSE stocks*

### 4. Portfolio Risk Measures
![Risk Measures](images/risk_measures.png)
*Distribution of optimal portfolio returns with Value-at-Risk (VaR) and Conditional VaR (CVaR) indicators*
