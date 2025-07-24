# Grocrey_Inventory_and_Sales_Dashboard
Dynamic Excel dashboard for grocery sales performance, using Power Query and PivotTables to transform raw data into actionable insights for optimizing sales and inventory.
# Data Source
Downloaded the Grocery Inventory and Slaes dataset from Kaggle.
Link- https://www.kaggle.com/datasets/salahuddinahmedshuvo/grocery-inventory-and-sales-dataset
# Data Description
This dataset provides detailed information on various grocery items, including product details, supplier information, stock levels, reorder data, pricing, and sales performance. The data covers 990 products across various categories such as Grains & Pulses, Beverages, Fruits & Vegetables, and more.
# Data Cleaning and Preprocessing 📊

During this project, rigorous data cleaning and preprocessing steps were undertaken to ensure the dataset's integrity and prepare it for robust analysis:

* **Data Transformation:** The raw `.csv` dataset was transformed into a usable Excel format using Power Query, maintaining data integrity throughout the process.
* **Missing Value Imputation:** Missing values in the 'Category' column were appropriately filled based on relevant product items to ensure comprehensive and robust analysis.
* **Data Type Formatting:** All datatypes were meticulously checked and accurately formatted according to their variable descriptions, preventing inconsistencies in analysis.
* **Feature Engineering - Sales Revenue:** An essential 'Sales Revenue' column was created by calculating `Sales_Volume * Unit_Price`, providing a key metric for financial analysis.
* **Categorical Feature Creation - Turnover Segment:** A 'Turnover_Segment' was defined based on the 'Inventory_Turnover_Rate' to categorize products, facilitating segmented analysis:
    * **High:** > 60
    * **Medium:** 20-60
    * **Low:** 0-20
# Dashboard Creation
All visuals and KPIs were dynamically created using PivotTables and PivotCharts for Summary Statistics and to visualize the trends, with strategic use of Slicers for interactive exploration.

# Key Performance Indicators (KPIs) Insights 📈

Analysis of the key performance indicators reveals crucial insights into operational efficiency and sales performance:

* **Total Sales Revenue:** Achieved **344,269.3** in total income from all product sales for the period 2024-25, highlighting overall financial performance.
* **Total Sales Volume:** Recorded **58,336** units, providing a clear understanding of the sheer volume of goods moved.
* **Average Sales Volume Per Product Sold:** An average of **58.925** units per product establishes a baseline for individual product performance. Products significantly exceeding this warrant attention as exceptional performers, while those falling below may require re-evaluation.
* **Zero Stock Products:** Currently, **none** of the products are completely out of stock, effectively preventing lost sales and enhancing customer satisfaction.
* **Stock-to-Sales Ratio:** A value of **0.9437** indicates efficient inventory management, where for every 1 unit of sales volume, approximately 0.9437 units are held in stock. This suggests the company is effectively meeting demand without significant overstocking or stockouts.

# Visual Interpretation & Core Findings 📊

Visualizations were instrumental in uncovering patterns and relationships within the data:

* **Product Categories Dominance:** "Fruits and Vegetables" combined with "Dairy" constitute over **50% of the total sales volume**, indicating these categories are primary revenue drivers.
* **Price-Volume Correlation:** No significant correlation was observed between 'Unit Price' and 'Sales Volume', suggesting pricing isn't the sole driver of sales quantity. The scatter plot also revealed outliers, indicating unique product performances that warrant deeper investigation.
* **Sales vs. Revenue Divergence:** The 'Top 10 products by Sales Volume' differ from the 'Top 10 products by Sales Revenue', primarily indicating that the products generating the most money are not necessarily the same as the products selling the most units.
* **Turnover Segment Performance:** Products categorized as 'High Turnover' (selling fastest) generate the most sales volume. 'Medium Turnover' products contribute a respectable amount, while 'Low Turnover' products generate the least sales volume, aligning inventory speed with sales contribution.


# Implications  🚀

 **Prioritize Star Performers (Fruits & Vegetables, Dairy):** Focus rigorously on ensuring consistent availability, optimal freshness, and competitive pricing for 'Fruits & Vegetables' and 'Dairy' categories. Any disruption in these areas could significantly impact overall revenue, as they constitute over 50% of total sales volume.
* **Segment-Specific Pricing Strategies:** Develop and implement more granular, segment-specific pricing strategies. The observed outliers in 'Unit Price' vs. 'Sales Volume' suggest unique product behaviors that warrant deeper investigation and tailored pricing approaches.
* **Optimize Inventory for Volume vs. Profit Drivers:**
    * **Volume Drivers:** Ensure these products are consistently well-stocked to maintain customer traffic and overall sales volume.
    * **Profit Drivers:** Optimize merchandising and pricing strategies for products that generate the most revenue (profit drivers) to maximize financial returns, even if they don't sell in the highest volume.
* **Efficient Replenishment for High Turnover Products:** Prioritize efficient replenishment cycles and strive for minimal stockouts for products identified with a 'High Turnover Rate', as these are generating the most sales volume.
* **Strategic Management of Low Turnover Products:** Implement aggressive liquidation strategies (e.g., discounts, bundles) for 'Low Turnover' products to free up capital and shelf space. Conduct a thorough review to determine whether these products should be stocked long-term, potentially optimizing inventory by delisting underperforming items.

# Files Included
* ** the raw data
* ** the cleaned data
* ** the dashboard

