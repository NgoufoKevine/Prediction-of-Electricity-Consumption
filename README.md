# Prediction-of-Electricity-Consumption
This project analyzes electricity consumption patterns using time series techniques to improve energy management. The study applies statistical and machine learning models to forecast electricity demand, identify seasonal trends, and optimize grid efficiency.

## Objectives
- Understand electricity consumption patterns.
- Examine seasonal differences in energy consumption.
- Forecast future electricity consumption using time series models.

## Methodology
1. **Comparison of Mean Electricity Consumption**: 
   - ANOVA test to determine significant seasonal differences in electricity usage.
   - Hypotheses:
     - H₀: µ₁ = µ₂ = µ₃ = µ₄ (No difference in seasonal consumption)
     - H₁: µ₁ ≠ µ₂ ≠ µ₃ ≠ µ₄ (Significant difference in seasonal consumption)
   - The ANOVA test result rejected the null hypothesis, indicating significant seasonal variations.

2. **Forecasting Electricity Consumption**:
   - The **SARIMA (Seasonal Autoregressive Integrated Moving Average)** model was used to capture trends and seasonal patterns in the electricity consumption data.

3. **Clustering Clients Based on Consumption Behavior**:
   - Used clustering techniques to group clients by consumption habits.
   - Helps in demand-side management, tariff structuring, and optimization.

## Dataset
- The dataset consists of electricity consumption records for **370 clients in Portugal**.
- Data was collected at **15-minute intervals** from **2011 to 2014**, totaling **140,256 observations**.
- Each record includes:
  - Timestamp
  - Electricity consumption (in kilowatts)

## Results
- Seasonal consumption differences were statistically significant.
- The SARIMA model successfully captured consumption trends and provided reliable forecasts.
- Clustering identified distinct client consumption behaviors, supporting better energy planning.

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels)
- **Time Series Analysis** (SARIMA modeling, ANOVA tests)
- **Clustering techniques** for client segmentation

## Future Improvements
- Implementing deep learning models for improved forecasting accuracy.
- Testing alternative time series forecasting methods.
- Applying real-time analytics for dynamic energy management.
