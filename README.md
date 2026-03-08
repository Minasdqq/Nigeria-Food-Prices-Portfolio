# Nigeria Food Prices Portfolio

One real-world dataset → 4 portfolio projects (EDA, Visualization, ML Prediction, Time Series Forecasting).

All projects use the **World Food Programme (WFP) Nigeria Food Prices** dataset (2002–2026), covering staples like rice, beans, tomatoes, garri across states/markets.

## Why this portfolio?
- Demonstrates end-to-end data science skills using Nigerian economic data.
- Relevant to local issues (inflation, cost of living).
- Shows progression: basic analysis → beautiful viz → predictive modeling → forecasting.

## Projects

1. **[Exploratory Data Analysis (EDA)](./project-1-eda/README.md)**  
   Cleaning, patterns, insights on food price trends.

2. **[Data Visualization & Inflation Dashboard](./project-2-visualization/README.md)**  
   Charts, comparisons, seasonal heatmaps.

3. **[Machine Learning Price Prediction](./project-3-ml-prediction/README.md)**  
   Regression models (Linear, Random Forest) to predict prices.

4. **[Time Series Forecasting (Rice Focus)](./project-4-timeseries-forecast/README.md)**  
   Prophet & ARIMA for future price predictions.

## Dataset
- Source: World Food Programme – Nigeria Food Prices  
- Download: [Direct CSV (recommended)](https://data.humdata.org/dataset/wfp-food-prices-for-nigeria/resource/12b51155-0cd3-4806-9924-61ede4077591/download/wfp_food_prices_nga.csv)  
- Place in `/data/` folder locally (ignored by Git).  
- Notebooks can load directly: `pd.read_csv("https://.../wfp_food_prices_nga.csv")`

## Setup
```bash
pip install pandas numpy matplotlib seaborn scikit-learn prophet plotly openpyxl
