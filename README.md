# Sales-Data-Analysis – (Interactive Dashboard creation using MS Excel)

## Project Overview: 
This project is a Sales Dashboard built entirely in Microsoft Excel. It showcases key sales metrics and insights by importing, cleaning, and analyzing data from a CSV file. The dashboard provides interactive visuals to help stakeholders understand sales performance and make data-driven decisions.

## Project Objective: 
To design an interactive Excel dashboard that enables stakeholders to track and analyze monthly sales performance, including units sold, revenue, cost, and profit trends, across various products and countries. The dashboard supports data-driven decision-making by highlighting top-performing products, regional revenue contributions, and cost vs. revenue analysis through dynamic visualizations and slicers.

## Time Period Analyzed: 
The dataset covers the period from September 2019 to December 2020, capturing sales data across multiple countries and products during this 16-month span. This allows for analysis of both short-term trends and year-over-year comparisons.

## Dashboard: 
- <a href="https://github.com/priya-lathiya/Sales-Dashboard/blob/main/Dashboard.xlsx">Dashboard</a>
- <a href="https://github.com/priya-lathiya/Sales-Dashboard/blob/main/Dashboard.png">Dashboard Screenshot</a>

## Dataset used: 
- <a href="https://github.com/priya-lathiya/Sales-Dashboard/blob/main/Sales_data.csv">Sales_data</a>

## Tools Used: 
- Microsoft Excel
  - Power Query for data preprocessing
  - Pivot Tables and Pivot Charts for analysis
  - Slicers and conditional formatting for interactivity
- CSV data source

## KPIs:
1.	Units Sold: Total number of product units sold across all countries and months, as per the Units Sold column.
2.	Profit: Total profit earned, calculated as the difference between Revenue and Cost for each transaction.
- **Profit** = `Revenue - Cost`  
3.	Profit(%): Indicates how efficiently the company converts cost into profit.
- **Profit Margin** = `(Profit / Cost) * 100`
4.	Revenue: Gross income from product sales, recorded under the Revenue column.
5.	Cost: Total cost associated with producing or acquiring the products, from the Cost column.

## Questions:
1.	Among all the products, which one contributed the most to total revenue?
2.	Which country contributed the most to overall profit during the analysis period?
3.	Which product had the highest profit across all countries and months?
4.	During the period from September 2019 to December 2020, in which month did the profit show a significant increase?
5.	Which two products contributed the most to total profit in India?
6.	In which month did India generate the highest profit?
7.	Which two countries showed higher profit margins compared to others during the analysis period?

## Key Insights:
1.	Based on the total revenue analysis across all months and countries, the product **Chocolate Chip** contributed the highest revenue of **2971195**.
- This product alone accounted for approximately **35.89%** of the overall revenue, highlighting its importance in the product portfolio.  

2.	During the analysis period (Sep 2019 to Dec 2020), **United Kingdom** generated the highest total profit of **1066099**, making it the most profitable market for the business. This country contributed **21.85%** of the total profit across all markets.

3.	Chocolate Chip is the most profitable product across all countries and months, generating the total profit of **1782717**. It is also the most significant in cost and revenue.
  
4.	The most profitable months were June 2020, October 2020, and December 2020. -The sharp increase in June 2020 could be due to mid-year promotions. - October 2020 likely reflects festive season sales such as Diwali. - The spike in December 2020 may be attributed to holiday and New Year purchases.

5.	  In India, the two products that contributed the most to total profit were:
-	**Chocolate Chip**, which showed the highest overall profit,
-	Followed by **White Chocolate Macadamia Nut**.
Their popularity and consistent sales volumes throughout the analysis period made them the leading profit generators in the Indian market.

6.	In December 2020, india generated the highest profir. In December 2020, India generated the highest profit during the analysis period.

7.	India and the Malaysia had the highest profit margins among all countries during the analysis period.

##  Project Workflow:
1. **Data Import**
   - Imported the sales dataset (CSV file) into Excel.

2. **Data Cleaning**
   - Checked for missing values and formatting issues.
   - Standardized columns like date, revenue, cost, and product names.

3. **Data Modeling with Power Pivot**
   - Loaded data into the Power Pivot data model.
   - Created a unique **Date Table** to enable time-based filtering and analysis.
   - Established relationships between the Date Table and the main sales data.

4. **Dashboard Creation**
   - Built Pivot Tables using Power Pivot data model.
   - Created charts for Revenue, Profit, and Units Sold.
   - Added slicers to allow filtering by Date, Country and Month.

5. **Final Touches**
   - Cleaned up the design and formatting.
   - Tested the dashboard interactivity and calculations.
