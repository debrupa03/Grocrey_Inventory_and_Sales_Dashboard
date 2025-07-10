# Grocrey_Inventory_and_Sales_Dashboard
Dynamic Excel dashboard for grocery sales performance, using Power Query and PivotTables to transform raw data into actionable insights for optimizing sales and inventory.
# Data Source
Downloaded the Grocery Inventory and Slaes dataset from Kaggle.
Link- https://www.kaggle.com/datasets/salahuddinahmedshuvo/grocery-inventory-and-sales-dataset
# Data Description
This dataset provides detailed information on various grocery items, including product details, supplier information, stock levels, reorder data, pricing, and sales performance. The data covers 990 products across various categories such as Grains & Pulses, Beverages, Fruits & Vegetables, and more.
# Data Cleaning Steps and Handling 📊
·     Transformed the raw .csv dataset into a usable Excel format using Power Query, ensuring data integrity.
·     Appropriately filled missing values in the 'Category' column based on product items for robust analysis.
·     Ensured all datatypes were accurately formatted according to variable descriptions.
·     Created an essential 'Sales Revenue' column by calculating Sales_Volume*Unit_Price.
·     Defined 'Turnover_Segment' based on Inventory_Turnover_Rate to categorize products:
      High: > 60
      Medium: 20-60
      Low: 0-20
# Dashboard Creation
All visuals and KPIs were dynamically created using PivotTables and PivotCharts for Summary Statistics and to visualize the trends, with strategic use of Slicers for interactive exploration.
# Insights 💡
📈 Interpreting KPIs:

·   Total Sales Revenue- 344269.3, total income from all product sales in monetary terms for the period 2024-25
·   Total Sales Volume: 58336, gives a sense of the sheer volume of goods moving out of your store.
·   Average Sales Volume Per Product Sold: 58.925, gives a baseline for how well individual products perform on average in terms of quantity. Products selling significantly more than    this are exceptional performers, while those selling less might need attention.
·   Number of Products with Zero Stock: Currently, none of the products are completely out of stock, which prevents lost sales and customer dissatisfaction.
·   Stock-to-Sales Ratio: Helps assess inventory efficiency, the value 0.9437 indicates that for every 1 unit of sales volume, the company hold approximately 0.9437 units in stock.
The company is operating with efficiency and meet demand without significant overstocking or stockouts. 
📊 Interpreting the Visuals:

·    Product Categories- Fruits and Vegetables and Dairy together constitutes more than 50% of the total sales volume. 
·    No significant correlation is observed between Unit Price and Sales Volume. The scatter plot also indicates presence of some outliers, which indicates unique product performances worth deeper investigation.
·    Top 10 products by Sales Volume and Sales Revenue are different, primarily indicating that the products generating the most money are not necessarily the same as the products selling the most units.
·    Products that sell the fastest, High Turnover, are also generating the most sales volume. Products with a moderate selling speed, Medium Turnover, contribute a respectable amount to sales volume. Products that sell slowly, Low Turnover, generate the least sales volume.
# Implications  🚀
.    Star Performers-Fruits & Vegetables and Dairy. Focus should be on ensuring consistent availability, optimal freshness, and competitive pricing for these categories, any disruption here significantly impacts overall revenue. 
.    Pricing strategies need to be more segment-specific. Outliers suggest unique product behaviors.
.    Volume drivers should always be stocked to maintain customer traffic, while optimizing merchandising and pricing for Profit drivers to maximize financial returns.
.    Prioritizing efficient replenishment and minimal stockouts for the high products having High Turover Rate. 
.    Implementation of aggressive liquidation strategies (discounts, bundles) for Low Turnover products to free up capital and shelf space. To Review whether these products should even be stocked long-term.
# Files Included
. the raw data
. the cleaned data
. the dashboard

