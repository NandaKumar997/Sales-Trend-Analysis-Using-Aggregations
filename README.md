# Sales-Trend-Analysis-Using-Aggregations using MySQL
I have created Sales Trend Analysis Using Aggregations on online_sales.csv dataset uning MySQL.
The Key components/functions used in the query to extract the sales trend analysis are mentioned below.
YEAR(order_date) - Extracts the **year** from the 'order_date',                             
MONTH(order_date) - Extracts the **month** from the 'order_date',
SUM(amount) - Calculates **total revenue** per month ,                                     
COUNT(DISTINCT order_id) - Counts the **number of unique orders** (volume) per month ,
GROUP BY YEAR(), MONTH() - Groups results by year and month for aggregation ,
ORDER BY year, month - Ensures results are shown in **chronological order** ,
WHERE order_date BETWEEN -  (Optional) Filters data to a **specific time period** (e.g., Jan–Feb 2024) .
Revenue Trends spot the seasonal patterns and high/low-performing months.
Sales Volume will make us understand customer activity and order frequency.
Comparative Metrics used to compare different months or years side-by-side.
