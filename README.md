# Online vs In-Store Sales Analysis in Tableau 

## Purpose and Business Questions
This dashboard was designed to answer two key business questions:
- Among the 20 highest sales volume products, which product has the highest percentage of its sales via the online channel?
- Among the 20 highest sales volume products, which product has the lowest percentage of its sales via the online channel?

## Data Structure and Join Logic
- The analysis is based on a relational database with three tables: Product, SalesOrderDetail, and SalesOrderHeader.
- Tables were joined using Product ID and Sales Order ID to create a unified view of product-level sales across channels.

## Visualization Design 
- A horizontal bar chart was used to compare online vs in-store sales for each product.
- Key Tableau configurations:
- Rows shelf: Line Total
- Columns shelf: Name
- Color marks card: Online Order Flag
- Text marks card: Line Total with percentage formatting to show channel breakdown
- To improve readability and focus, the chart was filtered to display only the top 20 products by total sales volume, sorted top-down.

## Insights and Annotations 
- After calculating the percentage of online vs in-store sales for each product, I added annotations to highlight the products with the highest and lowest online sales share—directly answering the business questions.

<img width="1151" height="697" alt="Screenshot 2025-11-17 144626" src="https://github.com/user-attachments/assets/40636f3d-bac3-46db-97eb-ddf00c6cce32" />
