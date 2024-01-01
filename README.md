# WWalmart-Sales-Data-Analysis-
The objective of this project is to analyze the Walmart sales dataset to identify the best-performing stores and products, track sales patterns across various products, and understand customer purchasing behavior. The goal is to gain insights that can enhance and optimize sales strategies. The dataset, sourced from the Kaggle Walmart Sales Forecasting Competition, includes historical sales data for 45 Walmart stores across different regions, each comprising multiple departments. Additionally, the dataset incorporates holiday markdown events, which are known to influence sales, but predicting their specific impact on different departments presents a complex challenge.






Approach Used:

I)Data Wrangling: This is the first step where inspection of data is done to make sure NULL values and missing values are detected and data replacement methods are used to replace, missing or NULL values.
 1.Build a database
 2.Create table and insert the data.
 3.Select columns with null values in them. There are no null values in our database as in creating the tables, we set NOT NULL for each field, hence null values are filtered out.
II) Feature Engineering: This will help use generate some new columns from existing ones.
 1.Add a new column named time_of_day to give insight of sales in the Morning, Afternoon and Evening. This will help answer the question on which part of the 
   day most sales are made.
 2.Add a new column named day_name that contains the extracted days of the week on which the given transaction took place (Mon, Tue, Wed, Thur, Fri). This 
   will help answer the question on which week of the day each branch is busiest.
 3.Add a new column named month_name that contains the extracted months of the year on which the given transaction took place (Jan, Feb, Mar). Help determine 
   which month of the year has the most sales and profit.
III) Exploratory Data Analysis (EDA): Exploratory data analysis is done to answer the listed questions and aims of this project.
