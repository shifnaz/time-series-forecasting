# time-series-forecasting
Analyzing and forecasting time-dependent data for trend and seasonality detection.

# Time Series Analysis & Sales Forecasting (2021)

## 📌 Project Overview
This project involves analyzing and forecasting monthly sales data for a wine estate. It demonstrates the use of classical time series decomposition and forecasting models to predict future demand.

## 📊 Key Problems Solved
1. **Sales Trend & Seasonality Analysis:**
   - Analyzed two different product lines: **Sparkling Wine** and **Rose Wine**.
   - Identified **Multiplicative Seasonality** in Sparkling wine sales (peaks during holiday/festival months like Oct-Dec).
   - Identified a **Decreasing Trend** in Rose wine sales, providing critical business evidence for inventory reduction.
2. **Forecasting Models:**
   - Implemented **Triple Exponential Smoothing (Holt-Winters)** to capture both trend and seasonal fluctuations.
   - Built a 12-month sales forecast to assist in supply chain and inventory planning.
   - Evaluated model performance using **MAPE (Mean Absolute Percentage Error)** to ensure reliability.

## 🛠️ Technical Skills Applied
* **Time Series Decomposition:** Separating Trend, Seasonality, and Noise.
* **Forecasting Algorithms:** Simple, Linear (Holt), and Exponential (Holt-Winters) Smoothing.
* **Retail Analytics:** Translating statistical forecasts into actionable business recommendations (e.g., "Stock up in Q4," "Decrease Rose inventory").

## 💡 2026 Perspective
Looking back at this project, I see how my documentation standards have matured:
* **Code Commenting:** Today, I would include detailed comments within the code blocks to explain the choice between Additive vs. Multiplicative models and the tuning of smoothing constants (Alpha, Beta, Gamma), making the forecasting logic transparent for other analysts.
