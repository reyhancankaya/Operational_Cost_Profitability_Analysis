# Operational_Cost_Profitability_Analysis
BI project analyzing operational expenses and net profit margins using Python and Tableau.

# Operational-Cost-Profitability-Analysis
This project focuses on analyzing a company's **Operational Expenses (OpEx)** and their direct impact on **Net Profit Margins** using Python and Tableau.

## Overview
Using synthetic financial data generated with Python, I developed a high-level Business Intelligence (BI) dashboard to help executives identify cost leakages and optimize regional performance. The core of the project is a **Financial Waterfall Chart** that bridges the gap between Gross Revenue and Net Profit.

## Tech Stack & Skills
- **Languages:** Python (Pandas, NumPy), SQL Logic
- **BI Tool:** Tableau (Advanced Dashboarding)
- **Concepts:** Data Engineering, Financial Waterfall Analysis, KPI Tracking, Conditional Alerting.

## Phase 2: Advanced Visualizations (Tableau)
Instead of simple bar charts, I implemented complex BI visuals to provide deeper insights:
- **Waterfall Analysis:** Used `RUNNING_SUM` calculations to show how Gross Revenue is reduced by specific costs to reach Net Profit.
- **Dynamic KPI Cards:** Designed high-impact KPI tiles with conditional formatting to show real-time performance.
- **Regional Heatmaps:** Color-coded performance maps to identify underperforming markets and geographic cost clusters.

## Key Business Insights
- **Margin Erosion:** Identified that Marketing Spend has the highest volatility and impact on the final margin in specific regions.

- **Efficiency Thresholds:** Any department with a margin below 15% is automatically flagged for a budget review, reducing manual audit time.

- **Operational Optimization:** The dashboard reveals that Logistics Costs are significantly higher in the LATAM region compared to North America.

## Project Structure
- **Operational_Costs_Python_Script.ipynb:** Python notebook for data generation, cleaning, and EDA.

- **Operational_Costs_Analysis.csv:** The final processed dataset used for visualization.

- **BI_Operational_Profitability_Analysis.twbx:** The complete Tableau Packaged Workbook containing all sheets and the final dashboard.

- **Dashboard_Preview.png:** High-resolution screenshot of the final executive dashboard.
