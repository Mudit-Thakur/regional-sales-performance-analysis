📊 Regional Sales Performance Analysis (2014–2018)

Exploratory Data Analysis (EDA) project analyzing multi-year regional sales data to identify revenue drivers, profitability patterns, customer value distribution, and geographic sales performance.

This project demonstrates a complete data analytics workflow including data cleaning, feature engineering, exploratory analysis, and insight generation to support data-driven business decisions.

📌 Project Overview

Businesses generate massive amounts of sales data, but raw data alone does not reveal why revenue changes or which factors drive profitability.

This project analyzes historical sales transactions to uncover:

Key revenue drivers

Regional sales performance differences

Product profitability trends

Customer revenue concentration

Channel contribution to total sales

Seasonal sales patterns

The analysis transforms raw transactional data into clear business insights through visual analytics.

🛠 Tech Stack
Programming & Analysis

Python

Jupyter Notebook

Libraries Used

Pandas → Data cleaning & transformation

NumPy → Numerical operations

Matplotlib → Data visualization

Seaborn → Statistical visualizations

Plotly → Interactive charts and maps

📂 Dataset

Sales dataset representing multi-year transaction data across U.S. regions.

Dataset Coverage
Attribute	Description
Time Period	2014 – 2018
Geography	United States
Data Type	Transaction-level sales data
Industry	Consumer / Retail style dataset
Key Variables

Order Information

Order ID

Order Date

Sales Channel

Customer Information

Customer Name

Region

State

Product Information

Product Name

Unit Price

Quantity

Financial Metrics

Revenue

Profit

Profit Margin %

🔎 Project Workflow

The project follows a structured data analysis pipeline.

1️⃣ Data Cleaning

Removed inconsistencies

Standardized column names

Converted date columns

Checked missing values

Verified numerical data integrity

2️⃣ Feature Engineering

Additional analytical features were created including:

Profit Margin (%)

Monthly Revenue Aggregations

Customer Revenue Metrics

Regional Sales Metrics

These features help improve analytical depth and visualization clarity.

3️⃣ Exploratory Data Analysis

EDA was conducted to understand patterns across:

Time

Products

Customers

Regions

Sales Channels

Pricing vs Profitability

📊 Key Visual Analysis

The notebook includes a variety of data visualizations used in professional analytics workflows.

Revenue Trends

Monthly revenue trends were analyzed to identify seasonality and growth patterns.

Product Performance

Product-level analysis highlights top revenue generators and profit contributors.

Sales Channel Analysis

Evaluation of revenue contributions from different channels such as:

Wholesale

Distributor

Export

Geographic Sales Distribution

Regional and state-level analysis identifies high-performing markets across the United States.

Customer Value Distribution

Customer segmentation reveals revenue concentration among top customers.

Pricing vs Profitability

Scatter plot analysis evaluates the relationship between:

Unit price

Sales volume

Profit margins

💡 Key Business Insights
📍 Regional Sales Dominance

The West region generates the highest overall revenue, indicating strong demand and customer density.

📦 Product Revenue Concentration

A small number of products contribute a large portion of total revenue, suggesting strong product-market fit.

📊 Channel Dependency

Wholesale distribution accounts for a major share of total sales, highlighting the importance of bulk sales channels.

💰 Stable Profit Margins

Profit margins remain relatively consistent across most products, indicating effective pricing strategies.

👥 Customer Revenue Distribution

Most customers generate moderate revenue levels, while a small number of high-value customers contribute disproportionately to total sales.

📉 Weak Price–Margin Correlation

Higher unit prices do not always correspond to higher profit margins, suggesting cost structure and pricing dynamics influence profitability.

📈 Example Visualizations

The project includes visualizations such as:

📊 Revenue trend analysis

📦 Product performance charts

🧭 Regional sales comparison

🗺 State-level sales choropleth map

💰 Profit margin scatter analysis

📉 Price distribution boxplots

🔗 Correlation heatmap

(Charts available in the Jupyter Notebook)

🎯 Business Questions Answered

This analysis explores several important business questions:

Which regions generate the most revenue?

What products drive the majority of sales?

Which channels contribute the most revenue?

Who are the highest-value customers?

Are pricing and profit margins correlated?

What seasonal sales patterns exist?

📁 Repository Structure
regional-sales-analysis
│
├── mudit_regional_sales_eda_completed_final.ipynb
│
├── dataset
│   └── sales_data.csv
│
├── visuals
│   └── charts
│
└── README.md
🚀 Future Improvements

Potential extensions to this project include:

📊 Building an interactive Power BI or Tableau dashboard

🤖 Implementing sales forecasting models

📈 Creating customer lifetime value (CLV) analysis

🧠 Developing machine learning demand prediction

🗺 Building a geospatial sales intelligence dashboard

👤 Author

Mudit Thakur

Data Analyst focused on transforming raw data into business insights using Python, SQL, and BI tools.

⭐ If you found this project useful, consider starring the repository.
