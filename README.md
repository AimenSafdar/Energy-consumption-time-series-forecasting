# ⚡ Energy Consumption Time Series Forecasting

## 📌 Objective
Forecast short-term household energy usage using historical time-based patterns.

## 📂 Dataset
- **Name:** Individual Household Electric Power Consumption
- **Source:** UCI Machine Learning Repository
- **Size:** ~2 million records (2006-2010)

## 🛠️ Steps Performed
- Parsed and resampled time series data to hourly frequency
- Engineered time-based features (hour, day, month, weekend)
- Trained and compared 3 forecasting models
- Plotted actual vs forecasted energy usage

## 🤖 Models Used
| Model | MAE | RMSE |
|-------|-----|------|
| **XGBoost** | **0.4415** | **0.6119** |
| ARIMA | 0.5970 | 0.7999 |
| Prophet | 0.6549 | 0.8210 |

## 🏆 Best Model
**XGBoost** outperformed both ARIMA and Prophet by leveraging 
time-based features like hour of day, weekday/weekend, and month.

## 📊 Skills Gained
- Time series forecasting
- Feature engineering
- Model comparison and evaluation (MAE, RMSE)
- Temporal data visualization

## 🧰 Libraries Used
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels (ARIMA)
- Prophet
- XGBoost
- Scikit-learn

## 👤 Author
- **Name:** Aimen Safdar
- **Internship:** Data Science Intern
