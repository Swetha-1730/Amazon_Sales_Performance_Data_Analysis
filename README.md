# **Amazon Sales Performance Data Analysis**([Project_Report](https://github.com/user-attachments/files/17002484/Amazon.Sales.Performance.Data.Analysis.Documentation.Report.pdf))

## **Project Overview**
- This project focuses on analyzing Amazon's sales data to identify factors that impact profitability, operational efficiency, and customer satisfaction.
- The goal is to leverage data-driven insights to help Amazon stay competitive and optimize its sales strategies in a dynamic e-commerce market.


## **Business Problem**
- Amazon must continuously refine its sales strategies to maintain a competitive edge.
- Key challenges include:
  - Optimizing profitability
  - Improving operational efficiency
  - Ensuring high levels of customer satisfaction
- The objective is to perform a comprehensive analysis of sales data to identify opportunities for growth and refine sales tactics.

## **Dataset**
- The dataset includes 100 records with 14 attributes per transaction, sourced from XYZ Company.
- Key features:
  - **Region**, **Country**, **Item Type**, **Sales Channel**, **Order Priority**, **Units Sold**, **Unit Price**, **Total Revenue**, and **Total Profit**.

## **Tools Used**
- **Python**: Data cleaning and exploratory data analysis (EDA)
- **Pandas**: Data manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Power BI**: Interactive dashboards for advanced visualizations

## **Data Preparation**
- **Data Type Conversions**: Converted date columns to the correct format; categorical and numerical columns were properly formatted.
- **Handling Missing and Zero Values**: No missing or zero values found in relevant columns.
- **Outlier Detection and Removal**: Seven outliers in total revenue, total cost, and total profit were removed.

## **Key Metrics**
- **Total Revenue**: $104.42M
- **Total Profit**: $33.82M
- **Total Cost**: $70.41M
- **Profit Margin**: 32.45%
- **Average Unit Price**: $231.48
- **Average Unit Cost**: $156.37
- **Return on Investment (ROI)**: 48.03%

## **Analysis Insights**
- **Revenue Trends**: November and April are peak months, with August and December being the lowest.
- **Profitable Regions**: Sub-Saharan Africa leads in revenue and profit, while Central America and the Caribbean face challenges.
- **Top-Selling Items**: Clothes lead in units sold, while Cosmetics generate the highest profit.
- **Sales Channels**: Offline channels outperform Online in revenue and profitability.
- **Order Priority**: High-priority orders generate the highest profit, while medium-priority orders have the highest fulfillment costs.

## **Recommendations**
- **Optimize Sales Channels**:
  - Focus on improving the **Offline** channel, which generates higher revenue.
  - Enhance strategies for the **Online** channel through targeted promotions and cost-efficiency.
- **Leverage Strong Markets**:
  - Prioritize regions like **Sub-Saharan Africa**, and focus on high-performing countries like **The Gambia** and **Turkmenistan**.
  - Address challenges in regions like **Central America** and **the Caribbean**.
- **Product-Specific Strategies**:
  - Capitalize on high-profit items like **Cosmetics**.
  - Reduce costs for popular items like **Clothes** to improve margins.
- **Improve Order Management**:
  - Streamline fulfillment for **High-priority** orders.
  - Reduce fulfillment costs for **Medium-priority** orders.
- **Seasonal Strategies**:
  - Utilize peak seasons like November and February for targeted promotions and inventory planning.
  - Implement sales strategies to boost revenue during low-sales periods like August and December.

## **Limitations**
- **Data Completeness**: Potential gaps and inaccuracies may affect the results.
- **Temporal Constraints**: Analysis is based on historical data and may not capture current trends.
- **Profitability Factors**: Variations in cost structures and pricing strategies may not be fully analyzed.
