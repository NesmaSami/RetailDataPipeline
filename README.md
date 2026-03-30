# RetailDataPipeline
RetailDataPipeline: Complete workflow for handling retail sales data from Excel to SQL with cleaning and import
# RetailDataPipeline

## Project Overview
This project demonstrates the workflow of handling retail sales data from Excel to SQL Server. 
It includes data cleaning, CSV preparation, creating SQL tables, and importing data using Bulk Insert.

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

## Future Steps
- Perform data analysis using SQL queries across all tables
- Create insights and visualizations based on sales and customer data
- Perform statistical analysis in Excel (mean, median, mode, standard deviation, correlation, histograms, scatter plots) for deeper insights

## Files Structure
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
