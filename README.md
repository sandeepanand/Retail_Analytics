# Retail_Analytics

Context
The Challenge - One challenge of modeling retail data is the need to make decisions based on limited history. Holidays and select major events come once a year, and so does the chance to see how strategic decisions impacted the bottom line. In addition, markdowns are known to affect sales – the challenge is to predict which departments will be affected and to what extent.

# Content
You are provided with historical sales data for 45 stores located in different regions - each store contains a number of departments. The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks.

Within the Excel Sheet, there are 3 Tabs – Stores, Features and Sales

# Stores
Anonymized information about the 45 stores, indicating the type and size of store

# Features
Contains additional data related to the store, department, and regional activity for the given dates.

<br> Store - the store number
<br> Date - the week
<br> Temperature - average temperature in the region
<br> Fuel_Price - cost of fuel in the region
<br> MarkDown1-5 - anonymized data related to promotional markdowns. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA
<br> CPI - the consumer price index
<br> Unemployment - the unemployment rate
<br> IsHoliday - whether the week is a special holiday week

# Sales
Historical sales data, which covers to 2010-02-05 to 2012-11-01. Within this tab you will find the following fields:

<br> Store - the store number
<br> Dept - the department number
<br> Date - the week
<br> Weekly_Sales -  sales for the given department in the given store
<br> IsHoliday - whether the week is a special holiday week

# Tasks

1. Run a ANOVA-test to determine the Significant groups between Holiday v/s No-Holiday
2. Perform EDA to determine the aggregated sales(Sum & Avg) per store for each-year(52-weeks). Using this result, also identify whether the Sales were high during Holiday or No-Holiday by each year
3. Determine the Significant-Features marrying Sales data against Features data for all-stores combined
4. Cluster the Stores based on Features & determine the Store-segments
