# taxi-demand-forecasting-model

A model that predicts airport taxi demand using time-series forecasting. Implements seasonal decomposition and gradient boosting to achieve an RMSE of 43 (Requirement: < 48)."

### 🚀 Technical Highlights

* **Advanced Time-Series Analysis**: Leveraged **seasonal decomposition** to isolate underlying trends and identify distinct daily and weekly seasonality patterns in taxi demand.
* **Feature Engineering for Temporal Data**: Developed a robust feature set using **lag variables**, **calendar attributes** (hour, day of week), and **rolling means** to capture stochastic shifts and autocorrelation.
* **Statistical Rigor**: Implemented **rolling mean and standard deviation** visualizations to evaluate the stationarity of the time series and guide the preprocessing strategy.
* **Model Benchmarking & Selection**: Evaluated a suite of regressors including **Linear Regression**, **Random Forest**, and **LightGBM**, tuning hyperparameters to find the optimal balance between training speed and accuracy.
* **High-Precision Results**: Successfully delivered a production-ready model achieving an **RMSE of ~43**, significantly outperforming the project’s strict requirement for reliable real-world deployment.

### 📂 Repository Structure
* **`data/`**: Project dataset and location documentation.
* **`notebooks/`**: Contains the primary analysis: `taxi_demand_forecasting_analysis.ipynb`.
* **`requirements.txt`**: Project dependencies including `statsmodels` and `lightgbm`.
