# 🪙 Gold Price Analytics & Prediction

An end-to-end data analytics and machine learning project analyzing gold price movements using macroeconomic indicators and time-series modeling.

The project explores relationships between gold prices and key financial variables such as the US Dollar Index, crude oil, treasury yields, and equity markets.

---

# 📊 Project Objectives

The goal of this project is to:

• Analyze historical gold price movements  
• Understand macroeconomic drivers of gold  
• Build predictive models for next-day gold returns  
• Visualize trends and risk metrics using Power BI  

---

# 🧠 Data Sources

Data was collected using **Yahoo Finance API** through Python.

Assets included:

- Gold ETF (GLD)
- US Dollar Index (DXY)
- Crude Oil Futures
- US 10Y Treasury Yield
- S&P 500 Index

Historical data range: 2021 – Present


---

# 🛠 Tech Stack

Python  
Pandas  
NumPy  
Scikit-learn  
Jupyter Notebook  
Power BI  

---

# 📁 Project Structure
gold-price-analytics/

│
├── 01_data_pull_clean.ipynb
│ Data extraction and cleaning
│
├── 02_eda_features.ipynb
│ Feature engineering and exploratory analysis
│
├── 03_modeling.ipynb
│ Machine learning models and evaluation
│
├── gold_macro_features.csv
│ Final dataset used for analysis
│
├── Gold_Analytics_Report.pbix
│ Interactive Power BI dashboard
│
└── README.md


---

# 🔎 Feature Engineering

Several financial indicators were created to improve analysis:

### Returns
Log returns were calculated:
Return = ln(Pt / Pt-1)


### Rolling Volatility
30-day rolling volatility was calculated and annualized.

### Moving Averages
- 20-day moving average
- 50-day moving average

### Drawdown
Maximum peak-to-trough decline from historical highs.

---

# 🤖 Machine Learning Models

Two models were implemented:

### Ridge Regression
Linear model with L2 regularization.

### Random Forest Regressor
Non-linear ensemble model.

The models predict: Next-day gold return

Evaluation metrics include:

- RMSE
- MAE
- Directional Accuracy

Directional accuracy measures whether the model correctly predicts the **direction of price movement**.

---

# 📈 Power BI Dashboard

The Power BI report provides interactive analytics including:

### Overview Page
• Gold price trend  
• Rolling volatility  
• Latest gold price KPI  
• 1-month return KPI  

### Risk Metrics
• Drawdown analysis  
• Volatility spikes  

### Macro Relationships
• Gold vs Dollar Index  
• Gold vs Interest Rates  
• Gold vs Oil Prices  

---

# 📷 Example Dashboard Visuals

Power BI dashboard includes:

• Gold price time series  
• Volatility analysis  
• Macro-driver comparisons  
• KPI cards for market metrics  

---

# 🚀 Key Insights

Gold price movements show strong sensitivity to:

• US Dollar strength  
• Interest rate expectations  
• Market volatility  

Periods of economic uncertainty tend to correspond with increased gold demand and higher volatility.

---

# 📌 Future Improvements

Potential extensions of this project include:

• LSTM deep learning time-series models  
• Real-time API data integration  
• Web-based dashboard deployment  
• Portfolio risk modeling using gold as a hedge asset  

---

# 👩‍💻 Author

**Shriya Shetty**

Finance | FinTech | Risk Analytics  

Building projects at the intersection of finance and data science.


![alt text](image.png)
