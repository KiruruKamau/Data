# 📊 Kenya CPI Trend Forecasting (2014–2024)

**Can we model and forecast Kenya’s Consumer Price Index (CPI) trends from 2014 to 2024 to understand inflation patterns and predict future economic pressure?**

This project explores this question using Kenya's CPI data and applies the OSEMN data science framework: **Obtain, Scrub, Explore, Model, and Interpret**.

---

## 🔍 Project Overview

Kenya’s Consumer Price Index (CPI) is a crucial economic indicator that measures the average change in prices paid by consumers over time. This project analyzes CPI and inflation trends over a 10-year period and uses the Holt-Winters exponential smoothing method to forecast CPI for the upcoming year.

---

## 🧰 Tech Stack & Libraries

- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`

---

## 🧪 OSEMN Framework

### 📥 1. Obtain

The dataset used is titled:

> _Kenya's CPI and Consumer Prices From 2014-2024_

It contains monthly CPI values and overall inflation rates from January 2014 to December 2024.

### 🧼 2. Scrub

- Verified data contains **no nulls or duplicates**.
- Parsed and cleaned the `DATE` column using `pandas.to_datetime`.
- Ensured monthly data is aligned using Pandas `MonthEnd` offsets.

### 🔎 3. Explore

#### Descriptive Stats:
- **Date Range:** Jan 2014 – Dec 2024
- **CPI Range:** 107.17 to 205.90
- **Inflation Rate Range:** 2.7% to 11.7%

#### Visualizations:
- Line plot showing CPI trends over time.
- Scatterplot and regression line showing weak negative correlation between CPI and inflation rate.
- Notable economic dip in 2020 due to **COVID-19**.

### 🤖 4. Model

#### Forecasting Approach:
Used the **Holt-Winters Exponential Smoothing** model which accounts for:
- **Level** (baseline value)
- **Trend** (long-term increase)
- **Seasonality** (cyclical effects)

#### Forecast Results:
- Forecasts CPI values for 12 future months (2025).
- Predicted continued modest increase in CPI if current patterns hold.
  


#### Model Performance:
- Visual comparison between actual and fitted values indicates a good model fit.

### 🧠 5. Interpret

- CPI has steadily increased from 2014 to 2024, with disruptions in 2020 due to global economic shocks.
- The weak negative correlation between CPI and inflation suggests other factors influence inflation rates more significantly.
- The forecasted rise in CPI signals potential **inflationary pressure** in the near term, emphasizing the need for proactive economic policy.

---

## 📌 Key Takeaways

- The CPI is a strong indicator of purchasing power and economic pressure.
- Forecasting CPI helps policymakers and investors anticipate inflation trends.
- Holt-Winters model is a useful tool for short-term economic forecasting when trend and seasonality are present.

---

## 📁 Files

- `Kenya's CPI and Consumer Prices From 2014-2024 - Sheet1.csv` — Main dataset
- `Forecasting Inflation Trends in Kenya (2014–2024) Using CPI Data and Holt-Winters Model.ipynb` — Python notebook/script for analysis and modeling

---

## 📈 Future Work

- Extend forecasting to inflation rate.
- Compare multiple time series models (e.g., ARIMA, SARIMA).
- Integrate external economic indicators (e.g., oil prices, interest rates).

---

## 🙌 Acknowledgments

- Data sourced from Kenya National Bureau of Statistics.
- Analysis inspired by the OSEMN framework for structured data science projects.

---

## 📬 Contact

For questions or collaboration, reach out via [kamaukiruru@gmail.com].

