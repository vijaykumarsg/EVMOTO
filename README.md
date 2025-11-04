📘1. Project Overview

The Global Electric Vehicle (EV) Dashboard is an interactive Tableau project built to analyze worldwide trends in electric vehicle adoption, sales, and market performance.
The dashboard transforms raw EV market data into clear, visual insights for manufacturers, policymakers, and analysts to make informed business and environmental decisions.

🎯 2. Objectives

Analyze global and regional EV adoption trends.

Identify top-performing EV brands and models.

Compare battery range, cost, and efficiency metrics across markets.

Provide data-driven insights into the growth of sustainable mobility.

📊 3. Data Description

Dataset Components:

Brand / Manufacturer: EV brand name (e.g., Tesla, Nissan, BYD, Tata)

Model: Electric vehicle model

Country / Region: Market geography

Sales Volume: Total EV units sold

Price: Average market price per vehicle

Battery Range: Average distance per charge

Year: Year of release or sale

Data Source:
Data collected from public datasets and EV market reports; cleaned and formatted in Excel before Tableau import.

⚙️ 4. Data Cleaning & Transformation

Data preparation performed using Excel and Tableau Prep:

Removed missing or inconsistent values.

Standardized brand and country names.

Calculated additional fields:

Revenue = Sales × Price

Efficiency Index = Battery Range / Price

Market Share = Brand Sales / Total Sales

Ensured proper data types and date formatting.

💡 5. Dashboard Design

The dashboard includes three analytical views providing multi-level exploration:

Page 1: Global EV Overview

KPIs: Total Sales, Market Share, Average Price, Avg Battery Range

Visuals: World map for regional distribution, line chart for year-over-year growth

Page 2: Brand & Model Analysis

Bar chart comparing top EV brands by sales and revenue

Scatter plot: Price vs Battery Range (Efficiency comparison)

Filter options: Year, Region, Brand

Page 3: Market Insights

Trend analysis of EV adoption rates by region

Pie chart: Brand market share distribution

Highlighted KPIs for emerging markets

🧮 6. Calculations & KPIs

Total Revenue: SUM([Sales] * [Price])

Average Battery Range: AVG([Battery Range])

Market Share: [Sales] / TOTAL([Sales])

Efficiency Index: [Battery Range] / [Price]

These metrics provide insights into brand competitiveness, affordability, and technological advancement.

🧠 7. Key Insights

Global EV adoption increased by 40% YoY.

Tesla, BYD, and Hyundai lead in global EV market share.

European and Asian regions show the fastest adoption growth.

High-range, low-cost vehicles achieved top efficiency scores.

📈 8. Business / Analytical Impact

Helps stakeholders evaluate market opportunities by region.

Enables manufacturers to benchmark performance against competitors.

Supports environmental policy planning by visualizing EV penetration rates.

Provides data-driven foundation for forecasting future EV demand.

🧰 9. Tools & Technologies
Category	Tools Used
Data Visualization	Tableau Desktop
Data Preparation	Excel, Tableau Prep
Data Modeling	Calculated Fields, Filters, Parameters
Source Data	EV Market Dataset (CSV/Excel)
Documentation	Markdown, PowerPoint
👨‍💻 10. Author

Vijay Kumar S G
📧 viji03662@gmail.com


📎 11. Future Enhancements

Integrate real-time EV market data APIs for live tracking.

Add predictive modeling for EV sales forecasting.

Include insights on charging infrastructure and CO₂ reduction impact.
