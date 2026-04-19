
# Weather Trend Forecasting 

##  Project Overview
This project analyzes global weather data to forecast temperature trends and uncover environmental patterns using data science and machine learning techniques.

The dataset contains daily weather observations across multiple countries, including temperature, humidity, wind, and precipitation.

---

##  Objectives
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Build forecasting models
- Compare multiple models and improve accuracy using ensemble methods
- Analyze climate patterns and environmental relationships

---

##  Data Preprocessing
- Converted date column (`last_updated`) to datetime format
- Handled missing values using median imputation
- Removed duplicates
- Detected and removed outliers using IQR
- Normalized numerical features using MinMaxScaler

---

##  Exploratory Data Analysis (EDA)
- Time-series analysis of temperature trends
- Correlation heatmap of weather features
- Distribution analysis of precipitation
- Identification of relationships between humidity, pressure, and temperature

---

##  Models Used
- ARIMA (time series forecasting)
- Prophet (trend and seasonality modeling)
- Random Forest (machine learning approach)

---

##  Ensemble Model
Combined predictions from ARIMA, Prophet, and Random Forest to improve forecasting accuracy.

---

##  Evaluation Metrics
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

---

##  Advanced Analysis
- Anomaly detection using statistical thresholds
- Feature importance using Random Forest
- Climate analysis across countries
- Environmental impact analysis (humidity vs temperature)
- Spatial visualization using latitude & longitude

---

##  Key Insights
- Temperature trends show seasonal variation across regions
- Humidity has a noticeable correlation with temperature
- Certain regions consistently exhibit higher temperature averages
- Ensemble models provide more stable predictions than individual models

---

##⚙️ How to Run

```bash
pip install -r requirements.txt
