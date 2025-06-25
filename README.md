# Startup-Finanacial-kPI-Analysis (2022-2024)

This project presents an interactive financial KPI dashboard for an early-stage startup, focusing on key performance metrics such as Revenue, Burn Rate, Customer Acquisition Cost (CAC), Lifetime Value (LTV), and Cash Runway. The analysis is designed to help founders, analysts, and investors monitor financial sustainability and optimize decision-making.

## Project Goal

To build a dynamic, interactive dashboard that analyzes monthly financial data from 2022 to 2024 to:
          Monitor financial health and operational efficiency.
          Identify profit-draining trends and customer acquisition inefficiencies.
          Provide stakeholders with a real-time snapshot of startup performance.


## Dataset

- **File**: `Startup_Financial_KPI_Analysis_Data.csv`

## Tools Used

- **Tableau** – for interactive KPI dashboard and visuals
- **Python (pandas)** – for dataset generation
- **CSV** – as data source


##  KPIs 

| KPI                | Description                                                   |
|--------------------|---------------------------------------------------------------|
| **Revenue ($)**     | Monthly startup revenue                                       |
| **Burn Rate ($)**   | Net cash loss per month (`Expenses - Revenue`)               |
| **CAC ($)**         | Average cost to acquire one new customer                     |
| **LTV ($)**         | Lifetime value per customer                                   |
| **Runway (months)** | How many months of operation left based on current burn rate |
| **Revenue Growth %**| Month-over-month revenue growth                               |
| **New Customers**   | Monthly acquired customers                                     |


## Why This Analysis Matters

Startups operate under high uncertainty. This analysis provides clarity on:
        1.Whether revenue growth is sustainable
        2.If customers are profitable in the long term
        3.How long the company can survive (cash runway)
        4.How efficiently marketing dollars are spent (CAC vs. LTV)

        
## steps involved

1.**Data Preparation**
Loaded financial data from 2022–2024 CSV
Cleaned and formatted Month, Revenue, CAC, etc.
Created calculated fields (Burn Rate, Runway, Growth %, etc.)

2. **Dashboard Building in Tableau**
Line  with circle Charts: Revenue Growth over Time
Bar Chart: CAC vs LTV comparison , Burn Rate per Month
line Chart: Expenses & Revenue 
KPI Cards: Total Revenue, Average CAC, Avg Runway, New Customers, Avg LTV
Added filters (Year, Metric Type) and interactivity

4. **Formatting**
Removed headers/gridlines for a clean look
Arranged KPI cards using horizontal containers
Added color 



##  Deliverables



## dashboard Insights

- LTV consistently exceeded CAC, indicating positive ROI on customer acquisition.
- Burn rate decreased in late 2023 due to cost optimization.
- Runway dropped below 6 months in mid-2022 — triggered funding round.
- MoM Revenue Growth % showed seasonal trends tied to campaign spending.


## Outcome

A clean, interactive Tableau dashboard that:
Tracks and visualizes startup financial performance over 3 years
Helps leadership and investors quickly understand key metrics
Supports strategic decisions on spending, scaling, and fundraising




