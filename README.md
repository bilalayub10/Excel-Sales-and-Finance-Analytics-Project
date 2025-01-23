# Sales & Finance Analytics using Excel

## Project Overview
In this project, I analyzed **sales** and **finance** data using **Excel** to derive actionable business insights. The datasets come from **AtliQ Hardwares**, a company that sells hardware products like **keyboards**, **printers**, and other devices. The analysis covers sales and finance data from the company’s **fiscal years** (1st September to 31st August) of **2019, 2020, and 2021**.

## Project Objectives

The main objectives of this project were to:
- Analyze **sales performance** across different customers and markets over three years (2019–2021).
- Evaluate the company’s **market performance vs target** to identify areas of overperformance and underperformance.
- Assess the **growth trends** of key customers and their contribution to overall sales.
- Generate actionable insights through the creation of **sales reports**:
  - **Customer Performance Report** to analyze the sales growth for each customer.
  - **Market Performance vs Target** to compare actual sales against set targets.
- Perform **financial analysis** using **P&L Statements** to assess the company’s revenue and cost performance over time:
  - **P&L Statement by Fiscal Year** to track yearly changes in net sales, COGS, and gross margins.
  - **P&L Statement by Months** to identify seasonal trends and peak sales periods.
  - **P&L Statement for Markets** to analyze how different markets contributed to overall financial performance.

## Tools and Technologies

- **Microsoft Excel** – The primary tool used for data analysis, reporting, and visualization.
  - **Power Query** – Used for data extraction, transformation, and loading (ETL).
  - **Power Pivot** – Used for creating data models and managing large datasets.
  - **DAX** (Data Analysis Expressions) – Used to create calculated columns and measures for analysis.
  - **PivotTables** – Used for creating dynamic reports and analyzing data trends.
  
## Data Structure
- The datasets include **Sales Data**, **Product Information**, **Customer Data**, **Market Data** and **Targets Data** for **AtliQ Hardwares** over its fiscal years (2019, 2020, and 2021).
- Tables were linked using **Power Pivot** to allow for efficient data modeling and analysis.
- The data was merged to create a comprehensive dataset for in-depth analysis, using **Power Query**.

## ETL Process (Extract, Transform, Load)

1. **Extract**  
   - The first step involved extracting data from various sources into Excel, consisting of sales, product, customer, and cost data for the fiscal years 2019, 2020, and 2021.
   - The raw data was imported into **Power Query**, enabling seamless integration of multiple data sources into a unified workspace.

2. **Transform**  
   - After loading the data into **Power Query**, several transformation steps were performed to clean and prepare the data:
     - **Data Cleaning**: Duplicate records, missing values, and any inconsistencies were identified and corrected.
     - **Standardization**: Data formats were standardized to ensure consistency across the dataset (e.g., dates, currency values).
     - **Merging Data**: Various datasets were merged to create a comprehensive, unified dataset, ensuring that all relevant information was available for analysis.

3. **Load**  
   - Once the data was cleaned, transformed, and merged, it was loaded into **Excel** for further analysis.
   - The transformed data was then loaded into the **Power Pivot** data model, where relationships between different data sources were created to support complex calculations and analysis.

4. **Data Modeling**  
   - In **Power Pivot**, relationships were established among different datasets to enable comprehensive and efficient analysis.
   - These relationships allowed for more advanced analysis by linking tables logically, making it easier to perform calculations and derive insights across the data.

5. **DAX Measures**  
   - After setting up the data model, **DAX measures** were created to support the generation of **reports**.
   - **DAX (Data Analysis Expressions)** was used to define custom calculations needed for the reports, such as **profit margins**, **total sales**, and **growth rates**.
   - These measures allowed for **dynamic calculations** that could update based on the filters and selections in the reports, enabling an interactive and flexible analysis.

## Sales Performance Analysis

**1. Customer Performance Report**  
This report provides a deep dive into customer performance, focusing on **net sales** for each customer. The key insights are as follows:
- **Integration Stores** recorded the highest percentage change at **887.2%**, increasing from **0.2M INR in 2020** to **1.4M INR in 2021**.
- Major customers like **Amazon** and **AtliQ Exclusive** showed solid percentage changes of **218.9%** and **345.8%**, respectively.
- **Note**: **Nova** started its sales in 2021, so the percentage change between **2020 and 2021** is not meaningful for this customer.

**2. Market Performance vs Target Report**  
This report compares actual sales performance to the set sales targets for different countries. Insights include:
- The total sales across all countries in **2021** fell short of the target by **54.9M INR**, representing a deviation of **-8.4%** from the set goal.
- Despite missing the target, **India** had the smallest deviation at **-5.6%**, followed by **Portugal** at **-4.1%**, indicating relatively strong performance.
- Countries like **Poland (-15.3%)** and **Canada (-12.6%)** showed the highest percentage shortfalls, highlighting areas needing improvement in achieving sales targets.

### **Importance of Analyzing Sales Data**

Analyzing **sales data** is crucial for businesses to understand their performance and identify opportunities for growth. By examining customer behavior, sales trends, and market performance, companies can make informed decisions, adjust strategies, and optimize resources to maximize profits. **Reports** play a vital role in this process as they provide valuable insights into various aspects of sales performance, such as customer segmentation, target achievement, and market behavior. This helps businesses identify their top performers, understand customer needs, and forecast future sales trends more effectively, ultimately leading to better decision-making and stronger business outcomes.

## Financial Performance Analysis

**1. P&L Statement by Fiscal Year**  
This report presents the **Profit and Loss (P&L) statement** for the company by fiscal year. The key insights are as follows:
- The growth rate for **net sales** from **2020 to 2021** was **204.5%**, indicating a substantial increase in revenue, rising from **196.7M INR** to **598.9M INR**.
- The **Cost of Goods Sold (COGS)** saw a growth rate of **208.6%**, escalating from **123.4M INR** in **2020** to **380.7M INR**, which outpaced sales growth and may affect profitability.
- **Gross margin** increased by **197.6%**, from **73.3M INR** in **2020** to **218.2M INR**, reflecting effective revenue generation despite rising costs.

**2. P&L Statement by Months**  
This report breaks down the **P&L** on a monthly basis. Key insights include:
- **November and December** consistently emerge as the peak sales months across **2019, 2020, and 2021**, highlighting strong seasonal demand during the year-end period.

**3. P&L for Markets**  
This report provides the **P&L** analysis by market. Insights from this report include:
- **India** leads in **net sales** among all markets, reflecting its dominant contribution to overall revenue performance.

### **Importance of Analyzing Financial Data**

Analyzing **financial data** is crucial for understanding a business’s profitability, cost structure, and overall financial health. It helps companies identify areas of concern such as rising costs or declining margins, while also highlighting opportunities for revenue growth. **Financial reports** provide actionable insights that allow businesses to make informed decisions about budgeting, cost control, pricing strategies, and investments. By continuously monitoring financial performance through reports, companies can ensure that their strategies are aligned with their financial goals, driving long-term success and sustainability.

---

## Reports

You can access the detailed reports in PDF format through the following links:
- [P & L Statement by Fiscal Year (PDF)](link_to_your_report_1)
- [P & L Statement by Months (PDF)](link_to_your_report_2)
- [P & L for Markets (PDF)](link_to_your_report_3)

---







