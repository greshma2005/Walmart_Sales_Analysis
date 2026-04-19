# 🛒 Walmart Sales Analysis using SQL
## 🚀 Project Overview
- his project delivers a comprehensive end-to-end SQL-based analysis of Walmart sales data. It transforms raw transactional data into actionable business insights using advanced SQL techniques, feature engineering, and exploratory data analysis (EDA).
- The project simulates real-world retail analytics, helping stakeholders understand sales performance, customer behavior, and product trends.
## 🎯 Business Problem
- Retail giants like Walmart generate massive transactional data daily. However, without structured analysis, it is difficult to:
Identify top-performing products
Understand customer purchasing behavior
Optimize revenue across locations
Improve operational efficiency
- 👉 This project solves these challenges by leveraging SQL to extract meaningful insights from raw sales data.
## Dataset Used
- <a href="https://github.com/greshma2005/Walmart_Sales_Analysis/blob/main/Walmart%20Sales%20Data.csv.csv">Dataset</a>

## Analysis List:
- Product Analysis
- Perform an analysis on the data to gain insights into different product lines, determine the top-performing product lines, and identify areas for improvement in other product lines.

- Sales Analysis
- The objective of this analysis is to address the inquiry regarding the sales trends of the product. The outcomes of this analysis can assist in evaluating the efficiency of each applied sales strategy in the business and determining necessary modifications to increase sales.

- Customer Analysis
- This analysis is focused on identifying various customer segments, understanding purchasing trends, and evaluating the profitability associated with each of these customer segments.

## Approach Used
### 1. Data Wrangling
During this initial phase, the data is examined to detect any NULL or missing values, and strategies for data replacement are implemented to address and substitute these values effectively.
Build a database
Create a table and insert the data.
Select columns with null values in them. Null values are not present in our database because, in creating the tables, NOT NULL was specified for each field, effectively filtering out any null values.
### 2. Feature Engineering
This will help use generate some new columns from existing ones.
Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the day most sales are made.
Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This will help answer the question on which week of the day each branch is busiest.
Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine which month of the year has the most sales and profit.
### 3. Exploratory Data Analysis (EDA)
Conducting exploratory data analysis is essential to address the project's listed questions and objectives.

## Business Questions to Answer
### Generic Questions
- How many distinct cities are present in the dataset?
- In which city is each branch situated?
### Product Analysis
- How many distinct product lines are there in the dataset?
- What is the most common payment method?
- What is the most selling product line?
- What is the total revenue by month?
- Which month recorded the highest Cost of Goods Sold (COGS)?
- Which product line generated the highest revenue?
- Which city has the highest revenue?
- Which product line incurred the highest VAT?
- Retrieve each product line and add a column product_category, indicating 'Good' or 'Bad,' based on whether its sales are above the average.
- Which branch sold more products than average product sold?
- What is the most common product line by gender?
- What is the average rating of each product line?
### Sales Analysis
- Number of sales made in each time of the day per weekday
- Identify the customer type that generates the highest revenue.
- Which city has the largest tax percent/ VAT (Value Added Tax)?
- Which customer type pays the most VAT?
### Customer Analysis
- How many unique customer types does the data have?
- How many unique payment methods does the data have?
- Which is the most common customer type?
- Which customer type buys the most?
- What is the gender of most of the customers?
- What is the gender distribution per branch?
- Which time of the day do customers give most ratings?
- Which time of the day do customers give most ratings per branch?
- Which day of the week has the best avg ratings?
- Which day of the week has the best average ratings per branch?

### 🧑‍💻 Tools Used
- SQL (MySQL)
- Relational Database Systems
- Data Analysis Techniques
### 📬 Conclusion
- This project demonstrates how raw retail data can be transformed into powerful business insights using SQL. It highlights strong analytical thinking, problem-solving ability, and readiness for real-world data roles.


