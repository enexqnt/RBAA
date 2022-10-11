# RBAA
Regime Based Asset Allocation with Random Forest and Bayesian Inference

1. Prediction with Random Forest and Genetic Algorithm:
    * [Inflation 12 months ahead YoY inflation](https://github.com/enexqnt/RBAA/blob/main/Forecast%20-%20Inflation.ipynb) and [Recession nowcasting](https://github.com/enexqnt/RBAA/blob/main/Forecast%20-%20Recession.ipynb) (for out-of sample regime classification)
    * [One-month ahead asset returns](https://github.com/enexqnt/RBAA/blob/main/Forecast%20-%20Assets.ipynb)
2. [Portfolio Optimization](https://github.com/enexqnt/RBAA/blob/main/RBAA.ipynb)
   * Define the economics regimes:
   * Bayesian inference to combine predictions and past returns
   * Mean-CDaR Portfolio Optimization
   * Backtest

Data sources: Fred, Yahoo Finance
Required libraries: XGBoost, Riskfolio,Fredapi

![alt text](https://github.com/enexqnt/RBAA/blob/main/images/wealth.png)
![alt text](https://github.com/enexqnt/RBAA/blob/main/images/forecast.png)
![alt text](https://github.com/enexqnt/RBAA/blob/main/images/sharpe.png)
![alt text](https://github.com/enexqnt/RBAA/blob/main/images/recession.png)


