Electric Vehicle Dashboard - Tableau Project

This project presents an interactive Tableau dashboard built on a Electric Vehicles (EVs) from various countries. 
The goal is to explore and compare EV models based on key factors such as cost, performance, battery efficiency, safety ratings, and charging capabilities.

 Project Objective

Analyze EV models across global markets to discover patterns and trends.
Identify the most cost-efficient, safe, and high-performing electric vehicles.
Help users interactively explore the dataset via dynamic KPIs, maps, and charts.

Dataset Description

File Name:`Electric Vehicle.csv`

Total Records: 10,200  
Columns: 17

| Column Name                  | Description                                                           |
|-----------------------------|-----------------------------------------------------------------------|
| sl no                       | Unique identifier for each EV record                                  |
| brand                       | Name of the EV manufacturer                                           |
| country                     | Country where the EV is sold                                          |
| state                       | State where the EV is available                                       |
| city                        | City of sale                                                          |
| top speed kmh               | Maximum top speed of the EV in km/h                                   |
| battery capacity kWh        | Battery size in kilowatt-hours                                        |
| battery type                | Battery technology (e.g., Li-ion, NiMH)                               |
| efficiency wh per km        | Energy consumption in watt-hours per kilometer                        |
| range km                    | Driving range on a full charge in kilometers                          |
| fast charging power kw dc   | Power capacity for DC fast charging in kilowatts                      |
| fast charge port            | Type of fast charge port supported (e.g., Type 2, CHAdeMO)            |
| seats                       | Number of seats in the EV                                             |
| drivetrain                  | Drivetrain type (FWD, RWD, AWD)                                       |
| electric vehicle type       | Type of EV (BEV, PHEV, etc.)                                          |
| safety rating               | Safety rating score out of 5                                          |
| cost                        | Cost of the EV in local currency                                      |


Dashboard Features

- **KPI Cards:** Total EVs, Avg Cost, Avg Range, Battery Capacity
- **Bar Charts:** Top EVs by range, speed, or efficiency
- **Scatter Plots:** Efficiency vs Range, Cost vs Battery
- **Geo Maps:** EV model availability by country/state
- **Filters:** Brand, Battery Type, Safety, Drivetrain, Cost Range
- **Interactive Parameters:** Select Metric, Top N EVs

Tools Used

- Tableau (Data Visualization)
- Python (Data Preprocessing)
- Excel - CSV (Dataset format)
- Power Query (Data Cleaning)

