# NYC Yellow Taxi Trip Demand, Revenue & Tipping EDA

Exploratory Data Analysis (EDA) and SQL KPI pipeline on **6.4M+ NYC TLC Yellow Taxi trip records** using Python, Pandas, NumPy, SQLite, Matplotlib, and Seaborn.

## Key Workflow
1. **Data Cleaning & Feature Engineering:** Deduplicated 6.4M+ records, handled missing passenger/surcharge values, filtered fare/duration anomalies, and engineered `trip_duration_min`, `pickup_hour`, and `tip_pct`.
2. **SQL Business Analysis (SQLite):** Queried payment-method share, tipping disparities across payment types, and top 10 revenue-generating pickup zones (`PULocationID`).
3. **Visualizations:** Generated hourly demand curves (`hourly_taxi_demand.png`) and average fare comparisons by passenger count (`fare_by_passengers.png`).
