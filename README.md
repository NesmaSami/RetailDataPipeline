# RetailDataPipeline
RetailDataPipeline:  Retail Data Pipeline & Analytics Project
# RetailDataPipeline

## Project Overview
This project demonstrates an end-to-end workflow for handling retail sales data, starting from Excel and progressing to SQL Server, followed by data analysis and visualization.

It includes data cleaning, CSV preparation, SQL table creation, data import using Bulk Insert, and further analysis to extract business insights.
## Tables Included
- `EProducts` → Product details
- `EOrdersItems` → Order item details
- `EOrders` → Orders information
- `ECustomers` → Customer information

## Steps Completed
1. **Data Cleaning**
   - Checked for empty cells and duplicates
   - Standardized date formats

2. **Data Preparation**
   - Exported cleaned data as CSV files
   - Each table saved in its own folder

3. **SQL Table Creation & Data Import**
   - Created tables with appropriate data types
   - Used Bulk Insert to load CSV files into SQL Server
4- power bi visualization
- Build an interactive Power BI dashboard to visualize KPIs and insights
- Enhance data storytelling and business recommendations
- - Analyze revenue and profit performance
- Identify top-performing products
- Understand customer behavior by age group
- Evaluate the impact of cost and pricing
## 📊 Dashboard Features
- KPIs (Revenue, Profit, Profit Margin, Avg Order Value)
- Profit distribution (Histogram)
- Sales by category
- Product-level performance
- Customer segmentation (Age Group)
- Scatter plot (Cost vs Price analysis)

- ## 🔍 Key Insights
- Electronics category generates the highest revenue
- A small number of products drive most of the profit
- Customers aged 45–55 are the most active segment
- Strong positive relationship between cost and price

## 🛠 Tools Used
- SQL
- Excel
- Power BI

## Files Structure

RetailDataPipeline/
├── README.md
├── .gitignore
├── LICENSE
├── EProducts/
│     ├── create_table.sql
│     ├── bulk_insert.sql
│     └── EProducts.csv
├── ECustomers/
│     ├── create_table.sql
│     ├── bulk_insert.sql
│     └── ECustomers.csv
├── EOrders/
│     ├── create_table.sql
│     ├── bulk_insert.sql
│     └── EOrders.csv
└── EOrdersItems/
      ├── create_table.sql
      ├── bulk_insert.sql
      └── EOrdersItems.csv
