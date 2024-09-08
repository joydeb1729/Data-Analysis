## Problem 2: Product Sales Insights

You are given a dataset containing sales information for various products. Your task is to analyze the data and provide visual insights for the following:

1. **Total Sales by Product (Item):**
   - Calculate the total sales (`Sale_amt`) for each product (`Item`).
   - Visualize the total sales using a bar chart.

2. **Top-Selling Products:**
   - Identify the top 3 products (`Item`) with the highest total sales (`Sale_amt`).
   - Visualize the top-selling products using a bar chart.

3. **Monthly Sales Trend of Top Products:**
   - Calculate the total sales amount for each month for the top 3 selling products.
   - Visualize the sales trend over time using a line chart.

4. **Average Unit Price by Product:**
   - Calculate the average `Unit_price` for each product (`Item`).
   - Visualize the average unit price using a bar chart.

5. **Units Sold per Product Analysis:**
   - Calculate the total units sold for each product (`Item`).
   - Visualize the total units sold using a bar chart.

The goal is to explore various aspects of the sales data, such as identifying top-performing products, understanding sales trends, analyzing pricing strategies, and examining sales volume.

## Dataset

Ensure that you have a dataset containing at least the following columns:
- `Item`: Name or identifier of the product.
- `Sale_amt`: Sales amount of the product.
- `OrderDate`: Date when the order was placed.
- `Unit_price`: Price per unit of the product.
- `Units`: Number of units sold.
- `Region`: Region where the sale took place (if applicable).

## Instructions

- Use Python and relevant libraries such as `pandas`, `matplotlib`, and `seaborn` to perform data analysis and visualization.
- Ensure that all visualizations are clear, well-labeled, and properly formatted.
- Provide code and explanations in a Jupyter notebook or Python script.