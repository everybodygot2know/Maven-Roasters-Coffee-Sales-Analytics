# Maven-Roasters-Coffee-Sales-Analytics
This project analyzes 149,000+ transactional records from Maven Roasters, a fictional multi-location coffee chain operating in New York City (January–June 2023). The objective was to apply advanced Excel techniques to perform end-to-end business and supply chain analysis, including data cleaning, demand forecasting, inventory optimization, and risk analysis.

**Business Context**

Effective inventory and demand planning are critical for retail operations to balance ordering costs, holding costs, and stockout risk while maximizing profitability.

The goal of this project was to answer the following questions:

* What are the key sales trends and patterns across locations and product categories?
* How can inventory ordering be optimized to minimize costs while reducing stockouts?
* What demand forecasting methods provide the most reliable weekly predictions?
* How does demand uncertainty impact profit and stockout risk?

Tools Used:

* Power Query
* Pivot Tables, Pivot Charts, and interactive dashboards
* Inventory Optimization models (EOQ, Safety Stock, Newsvendor)
* Demand Forecasting (Moving Average and Exponential Smoothing)
* Monte Carlo Simulation for risk and profit variability analysis
* Data visualization and KPI tracking

Data Overview:

* Cleaned and organized large dataset with Data Dictionary, summary statistics, and business insights
* Inventory Optimization: Built EOQ, Safety Stock, and Newsvendor models to balance ordering costs, holding costs, and stockout risk
* Demand Forecasting: Developed Moving Average and Exponential Smoothing (α = 0.1 & 0.5) models for weekly demand prediction
* Risk Analysis: Conducted Monte Carlo simulation (1,000 trials) to evaluate profit variability and stockout probability
* Interactive Dashboard: Visualizations, KPIs, and slicers for real-time decision-making

## Project Highlights 

### Interactive Excel Dashboard
<img width="1358" height="443" alt="{41C9EC8E-C4B3-4FAD-B3CF-0711A3B449FC}" src="https://github.com/user-attachments/assets/97e5e0fa-2714-4ee8-acfe-87904c4b812c" />


### Monte Carlo Simulation Results (1,000 trials)
<img width="891" height="510" alt="montecarlo" src="https://github.com/user-attachments/assets/07f943be-6f80-409a-a1e3-d25b8ee455b3" />


### Demand Forecasting Models
<img width="771" height="459" alt="demand_forecasting1" src="https://github.com/user-attachments/assets/0cac5f5f-6f0a-4597-a790-3b9606bf1300" />


<img width="1595" height="462" alt="demand forecasting2" src="https://github.com/user-attachments/assets/20dbbcea-3d95-46fa-a255-c352b30fe3d0" />




### Inventory Optimization Insights
<img width="734" height="607" alt="EOQ" src="https://github.com/user-attachments/assets/03091fd1-704f-4bd0-b8d5-5d844f1d746d" />


<img width="1762" height="333" alt="SS OOQ" src="https://github.com/user-attachments/assets/7a487173-9d99-498a-b653-6a7a9ee84294" />



**Key Findings**

* Demand patterns varied significantly across the three locations, with notable differences in product mix and peak periods.
* The Newsvendor model provided better balance between overstocking and stockout risk compared to basic EOQ in high-variability scenarios.
* Exponential Smoothing with α = 0.5 generally outperformed Moving Average for weekly demand forecasting in this dataset.
* Monte Carlo simulation revealed high profit variability, highlighting the importance of safety stock and demand uncertainty planning.

**Business Recommendations**

* Apply Newsvendor logic for high-variability products (coffee, bakery) to better manage stockout risk and overstock costs.
* Utilize Monte Carlo simulation into planning processes to stress-test inventory decisions under uncertainty.
* Implement location-specific inventory policies rather than using uniform approach.

Original Source: Maven Roasters: Coffee Shop Sales & Revenue Data

(https://www.kaggle.com/datasets/agungpambudi/trends-product-coffee-shop-sales-revenue-dataset)

Created by Walter Keel | July 2026
