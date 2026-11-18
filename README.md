🛍️ Customer Shopping Behavior Analysis

📌 Project Overview

This end-to-end data analytics project explores customer purchasing patterns, demographic trends, product preferences, and discount behaviors. The workflow spans from raw data ingestion and cleaning in Python, to database querying and aggregation in SQL Server, and finally to interactive business intelligence visualization in Power BI.

📁 Repository Structure

Customer_Shopping_Behavior/
├── Business Problem Document.pdf            # Project scope, objectives, and key business questions
├── customer_shopping_behavior.csv          # Raw dataset containing customer transactions
├── cleaned_data.ipynb                      # Jupyter Notebook for data cleaning, wrangling, and preprocessing (Pandas)
├── cleaned_data.xls                        # Exported cleaned dataset ready for database import
├── quering_cleaned_data.sql                # SQL Server queries for KPI calculation, segmentation, and insights
├── CSB_dashboard.pbix                      # Interactive Power BI dashboard file
├── Customer Shopping Behavior Analysis.pdf # Final presentation / static export of findings and visuals
└── README.md                               # Project documentation


🛠️ Tools & Technologies Used

Python (Pandas, Jupyter Notebook): Data cleaning, handling missing values, formatting columns, rounding numeric fields, and exporting structured data.

Microsoft SQL Server (SSMS): Database creation, schema configuration, data type transformation, and analytical querying (GROUP BY, CASE statements, aggregations).

Microsoft Power BI: Data modeling, DAX measures, and interactive dashboard reporting.

🔄 Project Workflow

Business Understanding: Reviewed the core business problem and defined key metrics (revenue by category, discount rates, subscription impact, and customer demographics) outlined in Business Problem Document.pdf.

Data Cleaning & Preprocessing (cleaned_data.ipynb):

Loaded raw data from customer_shopping_behavior.csv.

Standardized column formatting, rounded review ratings, and ensured consistent data types.

Exported the processed dataset (cleaned_data.xls) for SQL ingestion.

SQL Data Analysis (quering_cleaned_data.sql):

Imported the cleaned dataset into SQL Server (CSB database).

Resolved formatting anomalies (such as stray quotation marks in IDs and decimal precision adjustments).

Wrote analytical queries to uncover top-discounted items, customer spending habits, and subscription trends.

Data Visualization (CSB_dashboard.pbix):

Connected Power BI to the cleaned dataset to build an executive-ready interactive dashboard.

Summarized key takeaways in Customer Shopping Behavior Analysis.pdf.

🚀 How to Use This Repository

Clone the repository:

git clone https://github.com/your-username/Customer_Shopping_Behavior.git


Explore the Data Cleaning: Open cleaned_data.ipynb in Jupyter Notebook or VS Code to review the Python preprocessing steps.

Run the SQL Queries: Import cleaned_data.xls (or the cleaned CSV) into SQL Server Management Studio (SSMS) and execute the scripts in quering_cleaned_data.sql.

View the Dashboard: Open CSB_dashboard.pbix in Power BI Desktop to interact with the visualizations, or view Customer Shopping Behavior Analysis.pdf for a quick static overview.

📊 Key Focus Areas Analyzed

Customer Demographics: Age groups, gender distribution, and geographic location performance.

Product & Category Insights: Top-performing items, seasonal trends, and size/color preferences.

Promotions & Loyalty: Impact of discounts (discount_applied), subscription status, and repeat purchase frequency.
