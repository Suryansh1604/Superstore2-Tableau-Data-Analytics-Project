# Superstore2 — Tableau Data Analytics Project
1. [Tableau Public Data Analytics Project](https://public.tableau.com/views/SuperStoreSalesandCustomerDashboard/SalesDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)   

2. [Tableau Desktop Data Analytics Project](https://github.com/Suryansh1604/Superstore2-Tableau-Data-Analytics-Project/blob/main/salesproject%20tableau.twb)
- Click on Download icon to download file after opening the second link

## Project Overview

This project involves performing a data analytics / business intelligence exercise using the *Superstore2* dataset and developing interactive dashboards with **Tableau**. The goal is to derive insights from sales data, identify patterns, generate visual narratives, and support decision-making for a retail business scenario.

## Problem Statement

The key business challenge is:

> *How can we analyze and visualize the Superstore sales data to uncover trends, performance across dimensions (region, category, product, time), and pinpoint opportunities or issues that inform strategic decisions?*

> The purpose of sales dashboard is to present an overview of the sales metrics and trends in order to analyze year-over-year sales performance and understand sales trends.

> This user story outlines the specifications for building two dashboards using tableau to help stakeholders, including sales managers and executives to analyze sales performance and customers.

Some sub-questions to address include:
1. 


– Present the data for each KPI on a monthly basis for both the current year[Line Chart 1]  
– Identify months with highest and lowest sales and make them easy to recognize[Line Chart 1]  


2. **Product Subcategory Comparison**


– Compare sales performance by different product subcategories for the current year   
– Include a comparison of sales with profit.  


4. **Weekly Trends for Sales & Profit**

   
– Present weekly sales and profit data for the current year.  
– Display the average weekly values.  
– Highlight weeks that are above and below the average to draw attention to sales & profit performance.  


Represent the distribution of customers based on the number of orders they have placed to provide insights into customer behavior and engagement.


6. **Top 10 Customers By Profit**


– Present the top 10 customers who have generated the highest profits for the company.  
– Show additional information like rank, number of orders, current sales, current profit and the last order date.  



*(You may already have a “Problem Statement.txt” in your repo.)*

## Repository Contents

Here’s a breakdown of key items in this repository:

| File / Folder | Description |
|----------------|-------------|
| `Problem Statement.txt` | The detailed problem statement / business questions to answer |
| `salesproject tableau.twb` | The Tableau workbook file containing dashboards, visualizations, and worksheets |
| `Data Model.png` | Visual depiction of how data tables relate (schema / model) |
| `README.md` | (This file) Project description, instructions, insights, etc. |

## Approach & Methodology

Below is a typical workflow / methodology you might follow (adapt as needed):

1. **Data Understanding & Cleaning**  
   - Inspect the dataset(s): fields, data types, missing values, duplicates.  
   - Clean / preprocess as needed (handle nulls, filter invalid entries, fix data types).  

2. **Data Modeling / Structuring**  
   - Define relationships, join tables if multiple datasets.  
   - Build a logical data model (star schema, dimension / fact tables).  
   - Possibly create calculated fields, hierarchies, or aggregations.

3. **Exploratory Data Analysis (EDA)**  
   - Analyze summary statistics, distributions.  
   - Drill down into dimensions (region, category, product lines).  
   - Time series analysis (sales/profit over months, quarters, years).

4. **Visualization & Dashboard Building in Tableau**  
   - Create charts: bar, line, map, heatmap, tree map, etc.  
   - Use filters, parameters, interactivity, actions.  
   - Combine visualizations into cohesive dashboards.  
   - Add story or narrative flow (dashboard navigation).  

5. **Insights, Recommendations & Conclusions**  
   - Summarize key findings.  
   - Offer actionable business recommendations.  
   - Note limitations, possible further work.

## Key Dashboard / Visuals

Some of the visual components you might (or already do) include:

- Bans of Total Sales, Total Profit and Total Quantity Sales
- Monthly trend of Sales, Profit and Quantity Sold  
- SubCategory Performance by Sales and Comparison of Subcategory Sales with Profit
- Weekly KPI(Profit and Sales) Trends 
- Average KPI(Profit and sales) values

- Bans of Total Order, Total Customers and Total Sales Per Orders
- Monthly Trend of Order, Customers and Total Sales Per Custoers
- Customer Distribution by different Order Size
- Top 10 Customers by Profit
- Additional Information of Previous Customers like rank, current profit, current sales and last purchase date

## Superstore Dashboard Key Insights (2020 – 2023)

### 2020 Dashboard Summary
- **Total Performance:** $484.25K in Total Sales and $49.54K in Total Profit.  
- **Product Drivers:** Phones and Chairs were the primary sub-categories generating the most sales and profit.  
- **Customer Base:** 595 Total Customers resulting in 969 Total Orders.  
- **Key Trend:** Monthly profit peaked late in the year (around month 11).  

### 2021 Dashboard Summary
- **Profit Efficiency:** Total Sales slightly dropped to $470.53K, but Total Profit increased significantly to $61.62K, reflecting improved margins and efficiency.  
- **Customer Activity:** Customer count declined to 573, but Total Orders increased to 1,038, suggesting stronger retention and repeat business.  
- **Average Value:** Average Sales Per Customer rose to 821.2.  

### 2022 Dashboard Summary
- **Substantial Growth:** Total Sales jumped to $609.21K and Total Profit rose to $81.80K.  
- **Customer Expansion:** Total Customers reached 638 and Total Orders climbed to 1,315.  
- **Value Increase:** Average Sales Per Customer increased to 954.9.  

### 2023 Dashboard Summary
- **Peak Performance:** The best performing year, with $733.22K in Total Sales and $93.44K in Total Profit.  
- **Product Shift:** Phones overtook Chairs as the top product in both sales and profit.  
- **Peak Customer Metrics:**  
  - 693 Total Customers  
  - 1,687 Total Orders  
  - Record 1,058 Average Sales Per Customer  

### Overall Conclusion
From 2020 to 2023, the company demonstrated accelerating growth in both sales and customer performance.  
- Total Profit nearly doubled over the four years.  
- Expansion in customer base and orders directly fueled profitability.  
- Phones emerged as the leading revenue and profit driver.  


## How to Run / View

1. Install / open **Tableau Desktop** (or Tableau Reader)  
2. Open the workbook file `salesproject tableau.twb`  
3. Ensure data source connection is correct (point to the appropriate data file or database)  
4. Interact with filters, drill down into dashboards  
5. (Optional) Export dashboards to PDF / image or host on Tableau Public / Server  

## References & Acknowledgments

- Based on the **Superstore** dataset often used in analytics / BI case studies  
- (If you used external tutorials / blogs / sample projects, list them)  
- Inspiration from Tableau community for dashboard design practices  

## Future Enhancements

Some possibilities for extending the project:

- Add predictive modeling (e.g. forecasting future sales)  
- Incorporate advanced analytics (clustering, anomaly detection)  
- Bring in external data (e.g. demographic, economic indicators)  
- Embed the dashboards in a web app or BI portal  
- Automate periodic data refresh and dashboard update  

---

> _“Visualization is storytelling with data.”_
