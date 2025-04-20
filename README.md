# Analysis and Forecasting of Tourist Flow in Ireland (2010–2025)

This project analyzes the inbound tourist flow to the Republic of Ireland from 2010 to 2025, using a combination of statistical methods and machine learning models. Special attention is given to seasonal variations and COVID-19-related anomalies.

## 🎯 Objective

To analyze historical tourism trends and develop a forecast model for tourist arrivals in 2025.

## 🧠 Methods Used

- **Statistical Analysis**: Normality testing, distribution fitting
- **Clustering Algorithms**: KMeans and DBSCAN
- **Forecasting Models**: Linear Regression and Prophet

## 🔍 Key Findings

- The tourist flow does **not follow a Poisson distribution**, but is closer to **normal**.
- **DBSCAN** outperforms **KMeans** on year-by-year data by better capturing annual patterns.
- **Prophet** produces reliable forecasts when accounting for seasonality and anomalies.
- The final forecast gives a detailed estimate for tourist arrivals in 2025.

## 🛠 Tools

- Python  
- Scikit-learn  
- Prophet  
- Statistical plotting tools (e.g., Q-Q plot)  

---

*This project was submitted by Maksim Aitov (Student ID: 2025069) as part of MSc in Data Analytics coursework at CCT College Dublin.*
