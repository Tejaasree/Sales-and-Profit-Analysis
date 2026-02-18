# Superstore Sales Dashboard – Sales & Profit Analysis (Power BI)
## Project Objective:
The goal of this project is to transform raw retail transactional data into meaningful business insights using data modeling, DAX calculations, and interactive visualizations. The dashboard helps analyze sales performance, profitability, and regional trends to support data-driven business decision-making.

- Analyze overall sales and profit performance
- Identify top-performing regions, categories, and products
- Monitor sales trends over time to identify seasonal patterns
- Compare performance across customer segments and geographic locations
- Develop KPIs to measure business performance and growth
- Build an interactive dashboard for executive-level reporting

- ## Dataset Used:
  <a href="https://github.com/Tejaasree/Sales-and-Profit-Analysis/blob/main/SuperStore%20Sales%20DataSet.xlsx">Superstore Sales Dataset</a>

The dataset contains transactional records including:

- Order ID, Order Date, Ship Date
- Region, State, City
- Category, Sub-category, Product Name
- Sales, Profit, Quantity
- Customer Segment and Shipping Mode

## Questions (KPIs):

- What is the total sales and total profit?
- Which region generates the highest revenue?
- Which product category and sub-category perform best?
- What are the monthly and yearly sales trends?
- Which customer segment contributes the most revenue?
- Which geographic locations generate the highest sales?
- How does sales performance vary across regions and time?

## Process: 
The following steps were followed to complete this project:

1. Data Collection

- Imported Superstore dataset from CSV file into Power BI

2. Data Cleaning and Preparation

- Checked for missing and inconsistent values
- Verified and corrected data types (Sales, Profit, Date fields)
- Prepared dataset for analysis and visualization

3. Data Modeling

- Structured dataset using proper relationships
- Applied data modeling techniques for accurate aggregation
- Created calculated columns and measures using DAX

4. KPI Development using DAX

Created measures such as:

- Total Sales
- Total Profit
- Total Quantity Sold
- Total Orders

Example DAX measures:

Total Sales = SUM(Superstore[Sales])

Total Profit = SUM(Superstore[Profit])

Total Quantity = SUM(Superstore[Quantity])

Order Count = COUNT(Superstore[Order ID])

5. Dashboard Development

Built interactive visualizations including:

- KPI Cards for Sales, Profit, Quantity
- Line charts for monthly sales and profit trends
- Bar charts for category and regional analysis
- Map visualization for geographic performance
- Interactive slicers for Region, Category, and Segment

6. Insight Generation

Analyzed trends and identified key business drivers including:

- Top-performing regions
- High-revenue product categories
- Seasonal sales trends
- Customer segment contribution

- Dashboard
<img width="1316" height="735" alt="1" src="https://github.com/user-attachments/assets/6e8bb61d-aa75-4188-b5c9-64ff42960e55" />
<img width="1311" height="737" alt="2" src="https://github.com/user-attachments/assets/5353094a-c651-4c7e-ab95-aa305cf9ffaa" />

## Project Insights:

- Total Sales: $1.60M
- Total Profit: $175K
- Total Quantity Sold: 22K units
- West region generates highest revenue ($522K)
- Office Supplies category contributes highest sales ($0.64M)
- Phones is the top-performing sub-category
- Sales and profit peak during Q4 (Nov–Dec)
- Consumer segment contributes highest revenue share

## Final Conclusion:

- The Superstore Sales Dashboard successfully identifies key business performance drivers across regions, products, and customer segments. The analysis shows that the West region, Office Supplies category, and Consumer segment are the primary contributors to revenue and profitability. Seasonal trends indicate strong sales performance during Q4, highlighting opportunities for strategic planning.



