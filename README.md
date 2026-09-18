# customer_behaviour_analysis
End-to-end customer shopping behavior analysis using Python, SQL, PostgreSQL, and Power BI.

Overview
This project analyzes customer shopping behavior using an end-to-end data analytics workflow. The analysis covers 3,900 purchase records and focuses on understanding customer demographics, purchasing patterns, discounts, subscriptions, product performance, and customer segmentation.

The project follows this workflow:
Python → Exploratory Data Analysis → Data Cleaning → PostgreSQL/SQL Analysis → Power BI Dashboard → Presentation

Dataset
The dataset contains customer demographics and purchasing behavior data.
Total Records: 3,900 purchases
Columns: 18
Missing Values: Present in the Review Rating column
Key Data Areas: Customer demographics, products, purchase amounts, discounts, shipping, subscriptions, and previous purchases.

Tools & Technologies
Python – Data loading, cleaning, and exploratory data analysis
Pandas – Data manipulation and analysis
PostgreSQL – Database storage and SQL analysis
SQL – Business questions and customer analysis
Power BI – Interactive dashboard and data visualization
Gamma – Project presentation/PPT creation

Project Steps
1. Data Loading
The dataset was loaded into Python using Pandas for initial analysis and preparation.

2. Exploratory Data Analysis
Performed initial exploration to understand:
Dataset structure
Data types
Summary statistics
Customer and purchase characteristics

4. Data Cleaning
Checked for missing values and handled missing Review Rating values using median imputation.

4. Feature Engineering
Created additional features to support analysis, including:
Age groups
Purchase frequency

5. PostgreSQL & SQL Analysis
The cleaned data was integrated into PostgreSQL and analyzed using SQL queries.
The analysis included questions related to:
Discount usage
Purchase amounts
Product performance
Customer segmentation
Subscription behavior
Top products within categories

7. Power BI Dashboard
An interactive Power BI dashboard was created to visualize the analysis and make the findings easier to understand.

8. Project Presentation
The analysis and findings were summarized in a presentation created using Gamma.
Dashboard
The Power BI analysis focuses on several areas of customer behavior, including:
Revenue by gender
High-value customers using discounts
Top-rated products
Shipping preferences
Subscription impact
Customer segmentation

Results & Key Insights
The analysis produced several insights into customer purchasing behavior:
Female customers generated slightly higher total revenue than male customers in the analyzed dataset.
Customers using discounts while spending above the average purchase amount were identified as high-value discount users.
Products such as Blouse, Dress, and Shirt were highlighted based on customer review ratings.
Express-shipping customers had a higher average purchase amount than standard-shipping customers in the analysis.
Customers were segmented into New, Returning, and Loyal groups based on purchasing behavior.
Repository Structure

Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
|__ PYTHON_CODE/
|   └── Customer_behavior_EDA.ipynb
|
├── python/
│   └── customer(python).csv( Import this in SQL Server)
│
├── sql/
│   └── customer_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── README.md
│
└── LICENSE


Data Analytics | Python | Pandas | Data Cleaning | Exploratory Data Analysis | SQL | PostgreSQL | Data Visualization | Power BI | Customer Segmentation | Business Analysis

Author

Khushboo Chopra

Aspiring Data Analyst | Python | SQL | PostgreSQL | Power BI
