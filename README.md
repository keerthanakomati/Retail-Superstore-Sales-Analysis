# Retail-Superstore-Sales-Analysis

Project Name: Retail Superstore Sales Analysis
 # Objective: 
 To analyze the sales data of a retail superstore to identify weak areas and potential opportunities to increase profitability. The report provides insights into total sales, costs, profits, quantities, discounts, and performance across different categories, segments, and regions.

# Data Source
File Name: `superstore_sales.csv` 

Description: The dataset contains transaction-level sales data of a retail superstore with the following fields: 
- Ship Mode
 - Segment 
- Country 
- City 
- State 
- Postal Code
 - Region
 - Category
 - Sub-Category
 - Sales 
- Quantity
 - Discount
 - Profit
 - 
# Data Preparation
1.	Data Import: - Imported the `superstore_sales.csv` file into Power BI.

2.	Data Cleaning:- Checked for and handled any missing values. - Ensured all columns had the correct data types. 
3.	Data Transformation: - Created necessary measures for calculations. - Aggregated data to provide summaries at various levels (e.g., by category, segment, region).
4. Measures: Total Cost = Total Sales - Total Profit

# Visualizations 

1. Overview Metrics:
- Card Visuals: for Total Sales, Total Cost, Total Profit, and Total Quantity.
- These cards provide a quick snapshot of key performance indicators.

2. Total Discount and Profit by Sub-Category: 
- Line Chart: to show the sum of discounts and profits across different sub-categories.
- Helps identify which sub-categories have high discounts and how they correlate with profits.
  
3. Total Sales and Profit by Category:
- Bar Chart: to display total sales and total profit for each product category.
 - Highlights the performance of major categories: Technology, Furniture, and Office Supplies.
   
 4. Sales and Profit Trend Over Category:
- Line Chart: to show the trend of sales and profit over time for each category. 
- Helps visualize the performance trend of each category.
  
5. Sum of Profit by State and Region:
 - Filled Map: to show the sum of profit across different states and regions. 
- Identifies geographical areas with higher or lower profits.
  
 6. Sum of Sales by Segment:
 - Pie Chart: to display the distribution of sales among different customer segments: Consumer, Corporate, and Home Office. 
- Shows the contribution of each segment to total sales.
   
7. Sum of Profit by Region:
 - Column Chart: to compare the profit generated in different regions.
 - Highlights regional performance, identifying areas with potential for improvement.

# 6. Interactive Features 
1. Slicers:
   - Added slicers for Segment, Region, and Category to allow users to filter the data interactively.
   - - Slicers make it easy to drill down into specific areas of interest.

# 7. Insights and Recommendations
 **1. Low Profit Margins:**
 - **Insight:** Furniture category has a lower profit margin compared to Technology and Office Supplies. 
- **Recommendation:** Re-evaluate the pricing strategy for Furniture. 
**2. High Discounts Leading to Losses:**
 - **Insight:** High discounts on certain sub-categories like Tables and Chairs are leading to significant losses.
 - **Recommendation:** Implement more stringent discount policies and approval processes.
 **3. Regional Performance:** 
- **Insight:** The Central region is underperforming in terms of profit compared to other regions. - **Recommendation:** Conduct market research to understand the low performance in the Central region and tailor marketing strategies accordingly. 
**4. Segment Performance:**
 - **Insight:** Consumer segment contributes the most to sales but may not have the highest profit margin.
 - **Recommendation:** Focus on improving profitability in the Consumer segment through targeted promotions and cost control.

# Conclusion:  The Retail Superstore Report provides comprehensive insights into sales performance, highlighting key areas of concern and opportunities for improvement. By leveraging Power BI’s interactive features, stakeholders can easily explore the data and make informed decisions to drive profitability.
