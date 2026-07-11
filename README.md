# mw-sales-dashboard-powerbi
Interactive Power BI dashboard analyzing a synthetic BMW sales dataset (2010–2024) — built to practice DAX, data modeling, and dashboard design for a data analytics portfolio.

BMW Sales Dashboard (Power BI)

⚠️ Data Disclaimer

This dashboard is built on a synthetic/sample dataset sourced from Kaggle and does not represent BMW's actual sales, revenue, or business performance. Total figures in this dashboard (253M units, $19T revenue) far exceed BMW Group's real-world global figures and are an artifact of the dataset's random generation — not real financial or sales data. This project is for portfolio and skills-demonstration purposes only and is not affiliated with or endorsed by BMW.

Overview


Tool: Microsoft Power BI
Dataset: BMW Sales Dataset — 50,000 rows, 2010–2024, 11 models, 6 regions

Columns: Model, Year, Region, Color, Fuel_Type, Transmission, Engine_Size_L, Mileage_KM, Price_USD, Sales_Volume, Sales_Classification


Dashboard Features


KPI cards: Total Sales Volume, Total Revenue, Number of Regions, Average Price, Number of Models
Total Sales by Model (sorted, with data labels)
Sales by Fuel Type (Diesel / Electric / Hybrid / Petrol) by model
Revenue by Region, broken out yearly as small multiples (2010–2024)
Sales by Transmission (Automatic vs. Manual)
Total Sales by Region (sorted bar)
Detail table with Model × Region breakdown and conditional formatting
Slicers: Year, Model, Region, Fuel Type, Transmission

Screenshots
<img width="8000" height="4564" alt="BMW analysis_page-0001" src="https://github.com/user-attachments/assets/90610a14-c395-441c-a5ff-7fb3fbe987da" />


Key Observations


Sales volume is close to evenly distributed across all 11 models, 6 regions, and 15 years — reflecting the dataset's random generation rather than real-world market patterns (real BMW sales are typically concentrated by model and geography).
Sales_Classification (High/Low) is the one genuinely non-uniform field in the dataset (~30% High, ~70% Low), making it a more interesting variable to explore than the raw volume totals

Skills Demonstrated

Power BI report design (KPI cards, slicers, small multiples, conditional formatting)
DAX measures
Data modeling and aggregation consistency across visuals
Critical evaluation of dataset scale/plausibility before presenting findings
