# Customer_Shopping_Behavior_Analysis
A leading retail company sought to understand the key factors driving consumer decisions, repeat purchases, and satisfaction across different demographics and sales channels. This project processes 3,900 transactional records through an analytical pipeline involving Python (Data Cleaning &amp; Preparation), PostgreSQL, and Power BI.

🛍️ Customer Shopping Behavior & Trend AnalysisAn end-to-end data analytics project exploring consumer purchasing patterns, demographic distributions, product preferences, and subscription trends to optimize retail marketing and sales strategies.   📌 Project OverviewA leading retail company sought to understand the key factors driving consumer decisions, repeat purchases, and overall satisfaction across different demographics and sales channels. This project processes 3,900 transactional records through a multi-step analytical pipeline involving Python (Data Cleaning & Preparation), PostgreSQL (Business Intelligence & Querying), and Power BI (Interactive Visualization).

🛠️ Tech Stack & ToolsPython (Pandas, NumPy): Data ingestion, handling missing values, column standardization, and feature engineering.   PostgreSQL & SQL: Data organization, schema design, and structured transactional analysis (aggregations, rankings, segmentation).   Power BI: Interactive KPI tracking, metric slicing, demographic mapping, and category revenue dashboards.   

🔄 Project Workflow & Methodology1. Data Preparation & Modeling (Python)Dataset Scale: 3,900 rows and 18 columns covering customer demographics, purchase metrics, and feedback.   
Data Cleaning: Handled missing values in the review_rating column using category-wise median imputation. Standardized column headers to snake_case.   Feature Engineering:Created an age_group column by binning customer ages.   
Calculated purchase_frequency_days to capture behavioral cadence.   Dropped redundant columns (promo_code_used due to high redundancy with discount_applied).   Database Integration: Loaded the cleaned DataFrame into PostgreSQL for advanced SQL querying.   

2. Exploratory Data Analysis & SQL InsightsPostgreSQL queries were executed to extract deep transactional insights:
 Revenue by Gender: Male customers generated significantly higher total revenue ($157,890) compared to female customers ($75,191).
 High-Spending Discount Users: Identified 839 customers who utilized discounts while maintaining an above-average purchase amount.
 Top-Rated Products: Gloves (3.86), Sandals (3.84), and Boots (3.82) topped the customer review charts.
 Subscription Breakdown: Non-subscribers make up 73% (2,847 customers) of the customer base, highlighting an untapped opportunity for loyalty conversion.
 Customer Segmentation: Classified buyers into Loyal (3,116), Returning (701), and New (83) segments based on purchase history.   Revenue by Age Group: Young Adults led revenue generation ($62,143), followed closely by Middle-aged ($59,197), Adult ($55,978), and Senior ($55,763) segments.
