# SNEAKERS-SALES
I used Excel and SQL to analyse sneaker sales, identify top brands and markets, and track monthly revenue across 2022.
Key findings
Metric	Result
Total revenue	$193,103.07
Units sold	1,097
Sales records	353
Average revenue per record	$547.03


- Brands and products. Nike and Adidas generated 54.3% of total revenue. The Off-White Hoodie was the highest-revenue individual product at $24,214.82.
- Monthly trends. July led with $32,073.43 in revenue. April recorded the lowest revenue at $17,176.88.
- Markets. Japan led by revenue at $31,587.39. Canada had the most sales records, with 59.
- Payments. Cash on delivery was the most frequently used method, with 102 records. Wallet payments generated the most revenue, at $54,540.15.
Method
I used the supplied sales amount to calculate revenue and summed the quantity column to calculate units sold. The source has no order ID, so I counted each row as one sales record. I built the Excel dashboard and checked its totals and breakdowns against SQL query results.
How to use the files
1. Open the Excel workbook and start on the Dashboard tab. The Breakdowns tab contains the supporting calculations.
2. To reproduce the SQL analysis, open the complete script in your SQL editor and run it once in an empty database. The script creates the table and inserts the data in batches. Run all batches before running the analysis queries.

Business recommendations
Review stock coverage for Nike, Adidas and the Off-White Hoodie. Test targeted promotions in Japan, Canada and Germany. Compare July sales across additional years before planning around a recurring seasonal peak.
