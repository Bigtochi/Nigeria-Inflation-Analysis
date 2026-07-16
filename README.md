# Nigeria Inflation & Cost of Living Analysis (1960–2024)

An analysis of Nigeria's inflation rate over six decades using World Bank data, 
examining how major economic and political shocks have shaped the cost of living.

## Key Findings
- Inflation has been highly volatile rather than steadily rising — swinging between 
  near-zero and peaks above 70% at different points since 1960
- The sharpest spike in the dataset occurs during the **1993–95 economic crisis**, 
  where inflation surged to its highest recorded level in the series
- A second major spike appears in the mid-1970s, followed by decades of relative 
  moderation through the 2000s
- Inflation has trended upward again since 2020, accelerating through the 
  **post-COVID period** and approaching 30% by 2024
- The **2016 recession** shows a more moderate but still visible bump compared to 
  the 1990s and post-2020 periods

## Data
Source: World Bank World Development Indicators (`API_NGA_DS2_en_csv_v2_279569.csv`), 
filtered to Nigeria's annual inflation rate, 1960–2024.

## Chart
![Nigeria Inflation Trend](nigeria_inflation_chart.png)

*Shaded regions mark three major periods: the 1993–95 crisis, the 2016 recession, 
and the post-COVID surge (2020–2024).*

## Tools
Python · pandas · matplotlib · Jupyter Notebook

## How to Run
1. Clone this repo
2. Open `nigeria-inflation-analysis.ipynb` in Jupyter
3. Run all cells — cleaned data is included in `nigeria_inflation_clean.csv`
