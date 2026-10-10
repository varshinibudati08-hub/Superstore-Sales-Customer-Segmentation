# Superstore Sales Performance & Customer Segmentation

## Objective
Analyse sales performance across categories, regions and time, and segment customers using RFM to identify who drives revenue.

## Dataset
Superstore sales dataset (Kaggle): 9,800 order rows, 793 customers, Jan 2015 to Dec 2018. The dataset has sales values only (no profit or discount columns), so profit analysis is out of scope.

## Tools
Python (pandas), SQL (SQLite), Jupyter Notebook, Power BI

## Approach
1. Cleaned data in pandas and loaded it into a SQLite database
2. SQL analysis: sales by category, region and month, top products and customers
3. Advanced SQL: HAVING, CTEs, window functions (RANK, LAG, running total)
4. RFM customer segmentation in SQL using NTILE and CASE WHEN
5. Built a 2-page Power BI dashboard

## Key Numbers
- Total sales: 2.26M
- Customers: 793
- Average sales per customer: about 2.85K

## Key Insights
- Technology is the top category; West is the top region and South the lowest
- Sales peak towards the end of each year and trend upward in 2018
- Champions are the largest sales segment (close to 1M of 2.26M)
- Two of the top 3 spending customers fall in the Lost segment, so win-back campaigns look valuable

## Recommendations
- Run win-back offers for high-value customers in the Lost segment
- Reward Champions with loyalty benefits
- Plan stock and promotions ahead of the year-end sales peak

## Dashboard
![Sales Performance](superstore%20performance%20dashboard.png)
![Customer Segmentation](customer%20segmentation%20dashboard.png)
## Files
- notebook: data cleaning and SQL analysis
- CSV files: query outputs used in Power BI
