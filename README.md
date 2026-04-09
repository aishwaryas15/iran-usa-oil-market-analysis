# 🛢️ Iran–USA Geopolitical Risk & Oil Market Analysis (2017–2026)

## Project Overview
I started this project out of curiosity — with escalating 
Iran–USA tensions making headlines, I wanted to investigate 
whether geopolitical conflict actually moves oil prices. 
What I discovered was far more nuanced than I expected.

## Key Insights
- **Sanctions hurt Iran's production** but didn't always 
  raise prices — COVID killed demand at the same time
- **The Ukraine War had a bigger price impact** than any 
  Iran-specific event, pushing Brent crude to an all-time 
  high of $133.18 in 2022
- **Iran recovered faster than expected** — production 
  bounced back to 4,600 Mb/d by 2024 despite sanctions, 
  suggesting weakened enforcement
- **2026 is the most volatile period** in the dataset — 
  Trump's maximum pressure campaign is creating the biggest 
  single-day price swings in 9 years

## Tools Used
- **SQL (SQLite)** — Data storage, cleaning and querying
- **Python (Pandas, Matplotlib, Seaborn)** — Analysis and 
  visualization
- **Power BI** — Interactive dashboard with navigation

## Data Sources
- Brent Crude Oil Prices — U.S. Energy Information 
  Administration (EIA)
- Iran Oil Production Data — EIA International Energy Data
- Geopolitical Events Timeline — Manually compiled from 
  Reuters, BBC, Al Jazeera

## Project Structure
iran-usa-oil-analysis/
├── data/
│   ├── raw/          ← Original CSV files
│   └── clean/        ← Cleaned datasets
├── notebooks/
│   ├── 01_data_loading_and_sql.ipynb
│   └── 02_analysis_and_visualization.ipynb
├── outputs/
│   ├── chart1_price_timeline.png
│   ├── chart2_critical_events.png
│   ├── chart3_iran_vs_price.png
│   ├── chart4_volatility.png
│   ├── chart5_rolling_average.png
│   ├── chart6_heatmap.png
│   └── chart7_sanctions_impact.png
├── database/
│   └── oil_geopolitical.db
└── README.md

## Key SQL Queries
- Average oil price per year
- Top 10 biggest single day price spikes
- Iran production vs average Brent price by year
- Geopolitical events timeline

## Python Analysis
- 7 professional charts analyzing price trends
- Rolling 30 and 90 day averages
- Volatility scoring by year
- Sanctions period impact comparison

## Dashboard
Built in Power BI with 2 interactive pages:
- **Main Dashboard** — KPI cards, price timeline, 
  events table, production chart
- **Deep Dive** — Correlation analysis, volatility, 
  sanctions impact, price range

## What I Learned
This project taught me that oil markets are driven by 
overlapping forces — geopolitical tension, pandemic demand 
shocks, and war all interact in unexpected ways. Iran–USA 
tensions set the stage, but it took the Ukraine war to 
truly break the $100 barrier. Meanwhile Iran's production 
recovery suggests that sanctions without enforcement 
lose their bite over time.

## Connect With Me
www.linkedin.com/in/YOUR-LINKEDIN-HERE