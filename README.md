# BI-360-Dashboard
This project consists of a Power BI dashboard with 5 unique views to analyze and visualize KPIs and business trends across the various departments at AtliQ Hardware. It provides actionable insights into finance, sales, marketing, supply chain, and executive operations, enabling the stakeholders to make informed decisions for strategic growth.

## Live Dashboard: _[Business Insights 360](https://app.powerbi.com/view?r=eyJrIjoiNTlkYTgxNzItODFkMS00OGE3LWE5Y2MtMTVlZWQ0MDlkZGJhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=558fb0f349cc570a5220)_
## Home Page :


  **1.** Created a _[Home Page](https://github.com/AbhiPundir98/BI-360-Dashboard/blob/main/BI%20360_Home.pdf)_ for navigating to different Views in the Dashboard.

  **2.** The tiles have navigation to their respective Views.

- **Last Refreshed Date:** Shows the last data when the database was refreshed

- **Values in Millions($):** Values in the Dashboard are in Millions $.

- **Sales data loaded till mmm/yy:** Shows the latest date upto which data was provided


## Finance View :

**1.** Created a Dashboard for _[Finance View](https://github.com/AbhiPundir98/BI-360-Dashboard/blob/main/BI%20360_Finance.pdf)_

- **KPI Visuals:** KPI Visuals for Net Sales, Gross Margin % and Net Profit %, compared with their benchmark values(Last Year/Targets).

- **Profit & Loss Statement** A summary of a company's revenues, expenses, and profits/losses over a given period of time.

- **Top/Bottom Customers & Products by Net Sales:** The bottom two visuals give insights into the Top & Bottom Customers and Products according to their Net Sales contribution.

## Sales View :

- **1.** Created a Dashboard for _[Sales View](https://github.com/AbhiPundir98/BI-360-Dashboard/blob/main/BI%20360_Sales.pdf)_
  
- **Customer Performance:** Customer Performance based on their Net Sales, Gross Margin and Gross Margin %.

- **Product Performance:** Product Performance based on their segements by Net Sales, Gross Margin and Gross Margin %, which can be drilled down to category and product level.

- **Performance Matrix:** Scatter Plot showing the distribution of Customers by Gross Margin % and Net Sales. It also has a slicer to filter customers by specific Gross Margin % values. Customers in the Top Right quadrant are having High Gross Margin % and High Net Sales.

- **Key Metrics by Products:** Donut Charts showing distribution of Net Sales, Total Post Invoice Deductions, Pre Invoice Deductions, COGS, Gross Margin
  
## Marketing View :

- **1.** Created a Dashboard for _[Marketing View](https://github.com/AbhiPundir98/BI-360-Dashboard/blob/main/BI%20360_Marketing.pdf)_

- **Product Performance:** Segement Performance against Net Sales, Gross Margin, Gross Margin %, Net Profit and Net Profit %, which can be drilled down to category and product level.
  
- **Region/Market Performance:** Region Performance against Net Sales, Gross Margin, Gross Margin %, Net Profit and Net Profit %, which be drilled down to Market level.

- **Performance Matrix with Gross Margin/Net Profit% Toggle:** Scatter Plot showing the distribution of Customers by to **Net Sales** and either **Gross Margin %** or **Net Profit %**. Customers in the Top Right quadrant are very Profitable.

- **Unit Economics:** Insights into distribution of COGS and Gross Margin, and a waterfall chart to explore Gross Margin, Net Profit, Operational Expenses trends.

## Supply Chain View : 

- **1.** Created a Dashboard for _[Supply Chain View](https://github.com/AbhiPundir98/BI-360-Dashboard/blob/main/BI%20360_Supply%20Chain.pdf)_

- **KPI Visuals:** KPI Visuals for Forecast Accuracy, Net Error and ABS Error compared with their benchmark values(Last year).

- **Accuracy/Net Error Trend:** Monthly Distribution of Net Error and Forecast Accuracy (cuurent vs last year) using a Line and Clustered Column Chart.

- **Key Metrics by Products:** Analysis of Product Segments by Forecast Accuracy% (current vs last year), Net Error, Net Error%, and Risk (Excess Inventory/Out of Stock).

## Executive View :

- **View objective:** 

- **1.** Created a Dashboard for _[Executive View](https://github.com/AbhiPundir98/BI-360-Dashboard/blob/main/BI%20360_Executive%20View.pdf)_

- **KPI Visuals:** KPI Visuals for Forecast Accuracy%, Net Sales, Gross Margin % and Net Profit % compared against their benchmark values(Last Year/Targets).

- **Revenue Distribution by Division and by Channel:** using two respective Donut Charts.

- **Key Insights by Subzone:** Analysis of Net Sales, Revenue Contribution %, Gross Margin %, Net Profit %, AtliQ's Market Share, Net Error %, and Risk, broken down by sub-zones. 

- **Yearly Trend of Net Sales, Gross Margin %, Net Profit % and PC Market Share %** using a Line and Clustered Colmun Chart.   


## Key Learnings:
- [x]	Generating a date table using Power Query.
- [x]	Using Bookmarks for toggling visuals.
- [x]	Using Report parameters for dynamic filtering of metrics in a visual.
- [x]	Deriving fiscal months and quarters using DAX logic.
- [x]	Establishing data model relationships in Model View.
- [x]	Creating calculated columns and tables.
- [x]	Used MySQL Database to load and retrieve the data.
