# Eco-423_VAR-model
A time series analysis of Vietnam's macroeconomic indicators (2010–2024) using Vector Autoregression (VAR). The notebook simulates quarterly data from annual trends and models interdependencies across GDP growth, manufacturing, technology, FDI inflows, and employment.

# Vietnam Macroeconomic Analysis (2010–2024)

This project performs an econometric analysis of Vietnam's economic performance using a Vector Autoregression (VAR) model. It uses simulated quarterly data based on annual macroeconomic indicators to understand the interrelationships between GDP growth, sectoral growth, FDI, and employment.

Key Indicators Modeled

- **GDP Growth (%)**
- **Manufacturing Sector Growth (%)**
- **Technology Sector Growth (%)**
- **FDI Inflows (USD billions)**
- **Employment (millions)**


Methodology

1. **Data Simulation**
   - Annual indicator values (2010–2024) are interpolated into quarterly series.
   - Random noise is added to simulate real-world fluctuations.

2. **Stationarity Check**
   - Augmented Dickey-Fuller (ADF) test applied to each series.
   - Non-stationary series are differenced to ensure compatibility with VAR.

3. **Model Fitting**
   - Optimal lag order is selected using AIC, BIC, and other criteria.
   - A VAR model is fit on the stationary data.
   - Model summary reveals how current values of each indicator are influenced by past values of itself and others.
     
Outputs

- Descriptive statistics for all series.
- ADF test results and differencing where necessary.
- VAR model summary showing:
  - Regression equations for each variable.
  - Coefficients, standard errors, t-stats, and significance levels.
  - Residual correlation matrix.

