📊 E-Commerce Sales Dashboard

This project started as a simple attempt to analyze an e-commerce dataset, but during the process I faced multiple real-world data issues and learned how to clean, debug, and visualize data properly.

The goal was to understand how sales are changing over time, which products are performing well, and how different regions contribute to revenue.


📁 Dataset

* Source: Kaggle (E-commerce sales dataset)
* Contains order details, product info, region, and sales data


🔧 What I Did

1.Data Cleaning

* Removed missing values
* Fixed `sales` column (was not numeric initially)
* Handled inconsistent date formats in `order_date`
* Converted columns to proper data types

2.Analysis

* Aggregated sales monthly to see trends
* Identified top 10 products by revenue
* Compared sales across different regions

3.Visualization

* Created charts using Python (Matplotlib):

  * Monthly Sales Trend
  * Top Products
  * Region-wise Sales
* Built a dashboard in Power BI to make insights easier to understand


⚠️ Challenges I Faced

This project was not smooth — I ran into multiple issues:

* Errors with column names (`Order Date` vs `order_date`)
* Date format issues causing parsing errors
* `sales` column not being numeric
Solving these helped me understand how real-world data actually behaves.


📈 Key Insights

* Sales increased steadily over the years, showing business growth
* A small number of products contribute most of the revenue
* Some regions perform significantly better than others
* Overall trend indicates strong scalability potential


📊 Dashboard

The Power BI dashboard includes:

* Total Sales KPI
* Sales trend over time
* Top-performing products
* Region-wise sales distribution


💡 What I Learned

* Data cleaning is the most important step in analysis
* Real datasets are messy and require debugging
* Visualization is not just about charts, but clarity
* Small mistakes in data types can break everything


🚀 Next Improvements

* Adding customer-level analysis
* Build a sales prediction model
* Improve dashboard interactivity


👤 Author

ASHWIN RAJENDRAN


