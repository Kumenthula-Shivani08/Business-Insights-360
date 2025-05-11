## Problem Statement
AtliQ Hardware sells electronics like PCs, mouse, and printers in many countries. They use Excel to track their data, but it's slow, has errors, and doesn’t give clear insights. As the company grows, this makes it hard to make good decisions. This has led to losses in places like Latin America. AtliQ needs a better way to use their data and make smarter decisions.

## 🛠️ Tools & Technologies

- **Data Visualization:** Power BI  
- **Data Modeling:** Snowflake Schema, DAX  
- **ETL Tools:** SQL  
- **Tools:** Power BI Desktop, Power BI Service  

## 📁 Data Tables Overview

| **Source** | **Table Name**              | **Description**                                |
|------------|-----------------------------|------------------------------------------------|
| **MySQL**  | **Fact_Forecast_Monthly**   | Forecasted monthly product demand              |
| **MySQL**  | **Fact_Sales_Monthly**      | Actual monthly sales data                      |
| **MySQL**  | **Fact_Manufacturing_Cost** | Monthly manufacturing cost data                |
| **Excel**  | **Target**                  | Monthly sales targets                          |
| **Excel**  | **Market_Share**            | Market share data of competitors               |

# Power BI Features Implemented

## Data Exploration & Modeling
- Conducted data exploration using SQL queries.
- Designed a data model with **Star** and **Snowflake** schemas.
- Created a **Date Dimension** using **DAX** language for time-based analysis.

## DAX Measures & Customizations
- Developed **DAX measures** and calculated columns for advanced analysis.
- Set up **KPI Indicators** to track business performance.
- Created **dynamic titles** that change based on filter selections.

## Visual Interactivity & Navigation
- Implemented **Page Navigation** using buttons for a smoother user experience.
- Added **Toggle Buttons** to switch between different visuals.
- Designed **Interactive Bookmarks** for enhanced dashboard interactivity.

## Visual Enhancements
- Applied **Conditional Formatting** using icons and background colors for better data presentation.
- Enhanced the **Visual Appeal** of the dashboard for a more engaging user experience.

## Data Validation & Automation
- Set up **Data Validation Methods** to ensure data accuracy and integrity.
- Published reports to **Power BI Service** for online sharing and collaboration.
- Configured **Personal Gateway** to enable **Auto-Refresh** of data.

## Collaboration & Access Management
- Created a **Power BI App** for easy report access and distribution.
- Managed **Collaboration, Workspaces, and Access Permissions** in **Power BI Service** for better team coordination.

## Home Page 
![Home Page Preview](https://github.com/Kumenthula-Shivani08/Attachments/blob/main/home.png)

## 💰 Finance View   
- The dashboard provides a comprehensive view of financial performance for the year, compared to a benchmark.
- It includes key metrics like Net Sales, Gross Margin, and Net Profit to evaluate business performance.
- Monthly performance trends are displayed, highlighting both peaks and recovery points.
- It offers a detailed Profit & Loss breakdown, comparing actual results to the benchmark.
- Regional performance is analyzed, showing sales and growth across different regions.
- The dashboard allows for dynamic filtering by benchmark, time range, region, country, and product categories.
- Visualizations include charts and tables to show trends and performance over time.
- The main takeaway is that while sales have increased, rising costs and operational expenses have impacted profitability.


![Finance View](https://github.com/Kumenthula-Shivani08/Attachments/blob/main/finance.png)

## 📈 Sales View  
- Analyzes sales performance and profitability by customer and product.
- Shows how different customers contribute to Net Sales and Gross Margin, helping to identify key revenue drivers.
- Visual comparisons highlight key financial metrics such as sales, COGS, and gross margin.
- Many customers have high sales but low profitability due to declining margins.
- Top customers like Amazon and Atliq stores show strong sales but reduced gross margins.
- Rising costs and deductions are affecting profitability, despite strong sales growth.

   ![Sales View](https://github.com/Kumenthula-Shivani08/Attachments/blob/main/sales.png)
## 📢 Marketing View  
- Provides an overview of product and regional performance with a focus on sales, margins, and costs.
- Highlights how each region performs in terms of sales and profitability.
- Shows which product segments are performing well based on sales and gross margin.
- Identifies products and regions that have strong sales but low profitability.
- Visualizes the impact of operating expenses and cost of goods sold on overall margin.
- Helps identify areas where profitability is declining despite strong sales.


   ![Marketing View](https://github.com/Kumenthula-Shivani08/Attachments/blob/main/marketing.png)

## 🚚 Supply Chain View   

   ![Supply Chain View](https://github.com/Kumenthula-Shivani08/Attachments/blob/main/Supplychain.png)

## 👔Executive View   
   A consolidated view for senior leadership that highlights key performance metrics across all business functions for strategic decision-making.

   ![Executive View](https://github.com/Kumenthula-Shivani08/Attachments/blob/main/Excecutive.png)
