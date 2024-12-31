# Order selling data Analysis
## First cleaning a data using a python 
# Data cleaning Overview

This project outlines a step-by-step process for dataset preparation and preprocessing. The key steps are:

1. **Import Necessary Libraries**: Load essential libraries like `pandas` for data handling and `zipfile` for extracting files.
2. **Download Dataset**: Use the Kaggle API to fetch the required dataset.
3. **Extract Dataset**: Unzip the compressed dataset for access.
4. **Load Dataset**: Read the dataset into a pandas DataFrame for exploration.
5. **Handle Missing Values**: Identify and replace missing or unknown values with NaN for consistency.
6. **Clean Column Names**: Standardize column names by converting to lowercase and replacing spaces with underscores.
7. **Explore Data**: Check unique values in specific columns to understand the data distribution.

These steps ensure the dataset is clean, consistent, and ready for analysis.

# Data analysis in a Mysql 
## First import a clean data in a mysql server
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/import.png)

## Find top 10 highest revenue generating product
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/top10.png)

## Find top S highest sel product in each region
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/top5.png)

## Month over growth comparison for 2022 and 2023 sales eq : jan 2022 vs jan 2023
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/compare.png)

## For each category which month had highest sales
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/month.png)

# Creating a dashboard 
## creating dashboard using a power bi
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/order_dashboard.pdf)

The dashboard provides various insights into the sales and performance data for different regions, segments, and categories.

Filters:
1. Ship Mode: Filters data based on shipping methods, including First Class and Same Day deliveries.
2. Segment: Data is segmented into Consumer, Corporate, and Home Office groups.
3. Category: Users can view data related to categories such as Office Supplies and Furniture.
4. Sub Category: Further filtering is possible by subcategories like Appliances, Art, Binders, and Envelopes.
5. Years: Data covers the years 2022 and 2023.
6. Region: Data is broken down into Central, East, South, and West regions.

Visualizations:
1. Sub_Category Cost & List Price: This section compares the sum of cost price and list price for various sub-categories, highlighting areas like Furniture and Bookcases.
2. Quantity: Shows the number of items sold in different regions, with the West leading in quantity, followed by the East, Central, and South regions.
3. Profit by Product Category: Compares total profit for different product categories, providing insights into which categories are the most profitable.
4. Total Buying by Month: Displays total buying amounts month-by-month, helping to identify trends and seasonal variations in purchasing behavior.
5. Total Selling in State: A geographical representation of total sales across different states in the U.S., with a color gradient indicating the sales volume.
6. Total Selling by Segment: Shows the distribution of total sales among the three segments, with the Consumer segment having the highest percentage, followed by Corporate and Home Office.

Key Metrics:
- Sum of total selling: 1.42M
- Sum of quantity: 6216
- Sum of discount: 11.62K
- Sum of profit: 35.59K
- Sum of sale_price: 350.03K

Detailed Data:
1. Sum of sale_price and Sum of profit by Month Name:
   - April: 25K
   - August: 11K
   - December: 43K
   - February: 103K (13K profit)
   - January: 26K (12K profit)
   - June: 0
   - March: 29K
   - May: 21K
   - November: 25K
2. Sum of total selling by sub_category:
   - Binders: 0.28M
   - Chairs: 0.28M
   - Phones: 0.19M
   - Accessories: 0.20M
   - Appliances: 0.12M
   - Storage: 0.10M
   - Tables: 0.08M
   - Total: 1.25M
3. Sum of total selling by state:
   - New York: 493.86K
   - Pennsylvania: 409.97K
   - Ohio: 299.03K
   - Massachusetts: 69.25K
   - Rhode Island: 53.96K
   - Maryland: 40.47K
   - Delaware: 25.05K
4. Sum of profit by Day:
   - Peaks at various days with a maximum of 3.8K on day 5 and 6.6K on day 30
5. Sum of total selling by segment:
   - Consumer: 948.12K (66.89%)
   - Home Office: 281.76K (19.88%)
   - Corporate: 187.56K (13.23%)
6. Sum of total selling by category:
   - Office Supplies: 574.82K
   - Technology: 387.44K
   - Furniture: 455.15K

This overview provides a comprehensive dashboard of sales performance, highlighting key metrics and trends that can inform strategic decisions.

## Creating a dashborad in excel 
![](https://github.com/komalshahu/-Order_sell_data_Analysis/blob/main/order_dashboard_using_excel.jpg)

The dashboard presents various insights into the sales and performance data for different regions, segments, and categories.

Filters
1. Ship Mode: Users can filter the data based on shipping methods, including First Class and Same Day deliveries.
2. Segment: The data is segmented into three groups: Consumer, Corporate, and Home Office.
3. Category: Users can view data related to different categories such as Office Supplies and Furniture.
4. Sub Category: Further filtering is possible by subcategories like Appliances, Art, Binders, and Envelopes.
5. Years: The data covers the years 2022 and 2023.
6. Region: The data is broken down into four regions: Central, East, South, and West.

Sub_Category Cost & List Price
- This section compares the sum of cost price and list price for various sub-categories, highlighting areas like Furniture and Bookcases.

Quantity
- This chart shows the number of items sold in different regions, with the West leading in quantity, followed by the East, Central, and South regions.

Profit by Product Category
- A comparison of total profit for different product categories, providing insights into which categories are the most profitable.

Total Buying by Month
- Displays the total buying amounts month-by-month, helping to identify trends and seasonal variations in purchasing behavior.

Total Selling in State
- A geographical representation of total sales across different states in the U.S., with a color gradient indicating the sales volume.

Total Selling by Segment
- This section shows the distribution of total sales among the three segments, with the Consumer segment having the highest percentage, followed by Corporate and Home Office.




