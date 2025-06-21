Overview:
This project was developed using a dataset focused on car sales across various states in the United States. The primary goal was to analyze sales trends, identify top performing car brands, and visualize meaningful patterns. The motivation behind this project stems from a personal interest in data visualization and dashboard creation. As someone who enjoys transforming raw data into clear and engaging reports, I saw this as an opportunity to apply and demonstrate my skills. The final report includes six visuals that help explain the data in a clear and simple way. These visuals show top car brands, sales by month, and other helpful insights. 

Data Structure:
The dataset used in this project contains over 500,000 rows of car sales data and includes 16 columns with detailed information about each sale. Some of the key columns in the dataset are:

Year – the year the car was made

Make – the car brand 

Selling Price – the price the car was sold for

Mileage – how many miles the car had at the time of sale

Body – the type of car body

Transmission – type of transmission 

State – the U.S. state where the sale happened

Condition – condition rating of the car

Seller – who sold the car

SaleDate – the date the car was sold

In addition to these, there are several other columns that provide more details about each vehicle and its sale.
To support time-based analysis, I added a separate Date table to the data model. This allows for easier filtering and grouping by month, year, and other time periods.

The final data model consists of:

A CarSales table (the main dataset)

A Date table (used for time based visuals and relationships)

This structure allows for flexible and organized reporting, especially when creating visuals like sales trends over time.


Findings from the Data:
After analyzing the car sales data using several visuals, I was able to discover some key insights:

Sales by Month:
February had the highest number of cars sold, with over 132,000 sales. In contrast, April and July had the lowest sales, with only around 1,000 cars sold in each of those months.

Top 10 Brands:
The visual showing the top 10 car brands sold revealed that:

Ford had the most sales, with over 60,000 cars sold.

Chevrolet followed with over 40,000.

Nissan came in third with over 30,000 sales.

Sales by Model Year:
The 2013 model year had the highest number of cars sold at over 75,000, with the 2012 model year close behind at 74,000.

Sales by Mileage:
Most cars sold had mileage between 20,000–39,999 miles, totaling around 101,000 sales.
Cars with over 100,000 miles were the second most commonly sold group.

Sales by State and Brand:
The state of Florida had the highest number of car sales, with over 30,000 cars sold. Within Florida, Toyota was the most popular brand, making up about 7,000 of those sales.

These findings help highlight patterns in customer preferences by time, location, brand, and car condition.



Data Preparation and Modeling:
Before creating the visuals in my report, I spent time cleaning and organizing the data to make it easier to work with and analyze. Here are some of the key steps I took during the data preparation process:

Changed Data Types:
I made sure each column had the correct data type (e.g., dates, numbers, text) so that calculations and visuals would work properly.

Replaced Values:
I cleaned up the data by replacing inconsistent or incorrect values, such as converting lowercase state codes to uppercase.

Removed Unnecessary Data:
I deleted columns and rows that weren’t useful for analysis to help keep the dataset focused and reduce clutter.

Extracted Columns:
I removed parts of text and Kept only parts that were needed.

Filtered Rows:
I applied filters to keep only the data I needed, such as removing blanks or irrelevant records.

Renamed Columns:
I gave columns clear and consistent names to make them easier to understand when building visuals and writing measures.

Changed Column Formats:
I updated the formatting of columns—for example, changing number formats to proper date formats.

Created a Date Table:
I built a separate date table and linked it to the main CarSales table. This allowed me to easily group and filter data by month and year.

Created DAX Measures:
I used DAX to create custom measures for important metrics such as cars sold. These measures helped power the visuals and provided clear insights.

