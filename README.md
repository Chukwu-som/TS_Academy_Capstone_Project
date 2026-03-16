# TS Academy Capstone Project - Group 16
## NOVARA COHORT 2025

---

## Project Title
**Time Series Analysis: Forecasting Monthly Truck Sales using SARIMA**

---

## Track
Track 3: Time Series Analysis

---

## Objective
Forecast monthly truck sales using time series modeling (SARIMA) after performing full exploratory data analysis and preprocessing.

---

## Dataset
- **Name:** Truck Sales Dataset
- **Source:** [Kaggle - Dummy Truck Sales for Time Series](https://www.kaggle.com/datasets/ddosad/dummy-truck-sales-for-time-series)
- **Rows:** 144
- **Columns:** Month-Year, Number_Trucks_Sold
- **Period:** 2003 - 2014

---

## Model Used
**SARIMA(1,1,3)(1,1,3,12)**
- p=1, d=1, q=3 (non-seasonal)
- P=1, D=1, Q=3, s=12 (seasonal - monthly)

---

## Results

| Metric | Value |
|--------|-------|
| MAE | 21.46 |
| RMSE | 25.96 |
| RMS | 25.96 |
| MAPE | 3.30% |

The MAPE of 3.30% indicates **excellent forecasting performance** (below 10% threshold).

---

## Project Structure
```
TS_Academy_Capstone_Project/
│
├── README.md
├── capstone_grp_16.ipynb        # Main notebook
└── Truck_sales_033633.csv       # Dataset
```

---

## Steps Followed
1. Data Loading & Overview
2. Data Preprocessing (Date conversion)
3. Missing Values Analysis
4. Numerical Features Analysis
5. Univariate Analysis
6. Time Series Plot with Trend Line
7. Seasonal Decomposition
8. Stationarity Testing (ADF Test)
9. Differencing (First-order & Seasonal)
10. ACF & PACF Analysis
11. Train-Test Split (80/20)
12. SARIMA Model Building
13. Forecasting & Visualization
14. Residual Analysis
15. Model Evaluation (MAE, RMSE, MAPE)
16. Model Diagnostics

---

## Group Members

| Name | Email | GitHub |
|------|-------|--------|
| Umar Yahaya | umarbebeji24@gmail.com | [GitHub](https://github.com/Umarvc01/CAPSTONE-PROJECT-ON-TIMESERIES-MODELING-) |
| Fagbayi Boluwatife Sandra | fagbayisandra.7@gmail.com | [GitHub](https://github.com/fagbayisandra7-create/TS_Academy_Capstone_Project_) |
| Awhen Denis | awhendenis018@yahoo.com | [GitHub](https://github.com/awhen-denis/TS_Academy_Capstone_Project-) |
| Shorunke Abdulazeem | itazeeem10@gmail.com | [GitHub](https://github.com/Azo-rocks/TS_Academy_Capstone_Project) |
| Ajimajasan Faith Olusola | faith.ajimajasan@gmail.com | [GitHub](https://github.com/SurMan2026/TS_Academy_Capstone_Project) |
| Musediq Adeniran | ademusediq@gmail.com | [GitHub](https://github.com/musediq/TS_Academy_Capstone_Project) |
| Amoke Joshua Chibuikem | joshuaolaniyi518@gmail.com | [GitHub](https://github.com/InsightTN/Capstone-Project.git) |
| Egbuna Chisom Ifechukwu | Chisomifechukwu@gmail.com | [GitHub](https://github.com/Chukwu-som/TS_Academy_Capstone_Project) |

---

## Acknowledgement
We appreciate God almighty, TS Academy management for the scholarship opportunity, our tutor Mr. Hart for the foundation of our knowledge, and all group members for their collaborative effort in completing this project.
