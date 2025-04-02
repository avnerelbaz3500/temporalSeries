# Time Series Analysis: Industrial Production Index - Aerospace Construction

## Project Description
This project aims to analyze and model the time series of the **Industrial Production Index (base 100 in 2021) - Aerospace Construction**, provided by INSEE ([source link](https://www.insee.fr/fr/statistiques/serie/010768165#Tableau)). The objective is to apply time series processing techniques, ARMA/ARIMA modeling, and statistical forecasting.

## Project Plan

### **Part I: Data Analysis**
1. **Understanding the Time Series**
   - Description of the economic sector.
   - Nature of the data and potential transformations (logarithmic, normalization, etc.).
   - Identification of possible data issues (seasonality, trend, missing values, etc.).

2. **Making the Series Stationary**
   - Detecting trends and seasonal patterns.
   - Applying necessary transformations: differencing, deterministic trend correction, etc.
   - Justification of the choices made.

3. **Data Visualization**
   - Graph of the raw time series.
   - Graph after transformation.
   - Analysis of visual characteristics.

### **Part II: ARMA Modeling**
4. **Selecting an ARMA(p,q) Model**
   - Justification of the chosen parameters p and q.
   - Estimation of model parameters.
   - Model validation (residual analysis, AIC/BIC criteria, stationarity tests).

5. **Building an ARIMA(p,d,q) Model**
   - Justification of the differencing parameter d.
   - Final model selection.

### **Part III: Forecasting**
6. **Defining the Confidence Region**
   - Equation for the confidence interval at level \\( \\alpha \\).

7. **Underlying Assumptions**
   - Justification of assumptions needed to establish the confidence region.

8. **Visualization of the Forecast**
   - Graph of the series with forecast and 95% confidence interval.
   - Interpretation of results.

9. **Open Question: Improving Prediction**
   - Analysis of an auxiliary stationary time series \\( Y_t \\) and its potential impact on the forecast of \\( X_{T+1} \\).
   - Conditions under which this information improves forecasting.
   - Methods for testing this hypothesis.

## Technologies and Packages Used
- **Language**: R
- **Main Packages**:
  - `tseries`: Statistical tests for time series.
  - `forecast`: Time series modeling and forecasting.
  - `ggplot2`: Data visualization.
  - `zoo`: Time series manipulation.
  - `quantmod`: Financial time series analysis.

## Expected Outcomes
- A detailed analysis of the time series properties.
- A validated and interpreted ARIMA model.
- A short-term forecast with a confidence interval.
- A discussion on improving forecasting using auxiliary series.

## Data Source
The data is available from INSEE: [Industrial Production Index - Aerospace Construction](https://www.insee.fr/fr/statistiques/serie/010768165#Tableau).
