# Pizza Place Sales Performance Analysis


![image alt](https://github.com/Cyndi-24/Pizza-Place-Sales-Performance-Analysis-Python/blob/main/pizzasales_analysis/images/pizzza_sales_image.png)

## Project Overview

Pizza Place Sales is a Python-based business analysis project focused on understanding the sales performance of a fictional pizza restaurant using transactional data.

## Project Objective

The objective was to identify the restaurant’s strongest and weakest sales periods, understand ordering patterns, evaluate product performance, and translate the findings into practical recommendations for staffing, inventory, promotions, and menu decisions.

## Data Source

The analysis uses the **Pizza Place Sales** dataset from Maven Analytics, containing one year of transactional data across orders, order details, pizzas, and pizza types.

## Analytical Questions

1. What was the total revenue generated during the year?
2. How many pizzas were sold?
3. How many unique orders were recorded?
4. How many different pizza types were available?
5. What was the average price of pizzas sold?
6. What were the peak ordering hours?
7. Which days of the week generated the highest sales?
8. Which pizzas were the top performers?
9. How did sales vary across the months of the year?
10. Which pizzas were underperforming?

## Technologies Used/SKills Demonstrated

* Python: This was the main programming language used for the analysis
* Pandas: This was used for data cleaning,merging the csv files and performing most mathematical operations
* Matplotlib and Seaborn: This was used for creating the data visuals
* Jupyter Notebook: This is the interactive environment used to document the analysis step by step

## Approach

The project followed three main stages:
1. **Data Preparation** – Imported, reviewed, cleaned, merged, and prepared the four related datasets for analysis.
2. **Performance Analysis** – Used Python to answer the defined business questions and explore revenue, ordering patterns, peak periods, pricing, and product performance.
3. **Business Interpretation** – Visualized key patterns, interpreted the findings, and translated them into practical recommendations for the restaurant.


## Data Cleaning & Preparation

Before analysis, the four datasets were reviewed and prepared to ensure consistency and usability.
- Inspected the structure, columns, and data types of each dataset.
- Checked for missing values and duplicate records.
- Merged the four related tables using their shared identifiers.
- Converted the date and time fields to appropriate formats for time-based analysis.
- Extracted relevant time components needed to analyze sales by hour, day, and month.
- Created the required sales calculations for the analysis.

The resulting dataset was then used to answer the defined analytical questions.

## Key Findings & Visualisation 

### Overall Sales Performance

- The restaurant generated approximately **$817,860 in total revenue** during the year.
- A total of **49,574 pizzas** were sold across **21,350 orders**.
- Each order contained approximately **2.3 pizzas on average**.
- The average pizza price was approximately **$16.49**.

These figures provide an overall view of the restaurant's annual sales performance and serve as a baseline for examining when sales occurred and which products contributed most.

### Peak Ordering Hours

Order activity was highest around **12:00 PM and 1:00 PM**, showing a clear lunchtime peak in customer demand.

![image alt](https://github.com/Cyndi-24/Pizza-Place-Sales-Performance-Analysis-Python/blob/main/pizzasales_analysis/images/peak_hours.png)

This suggests that the restaurant experiences its greatest order volume around lunchtime, making this an important period for operational planning.

### Sales by Day of the Week

**Friday recorded the highest sales revenue**, followed by Thursday and Saturday, while Sunday generated the lowest sales.

![image alt](

The pattern shows that stronger sales were concentrated toward the latter part of the working week and Saturday rather than across the entire weekend.
# Recommendations and Conclusion


a) From the analysis the peak hours of sales were between *12 - 1 pm*  and the busiest day of the week is usually *Fridays* .Based on this there must be proper stocking during this Strategic periods to avoid shortages and there should be sufficient staff on ground during these period to meet up with the customer order.

b) Proper investigation should be carried out to find out the rason behind the flunctuations in sales trend. This will help in guiding sales optimization during seasons of poor sales.

c) Low peforming pizza in terms of volume ordered  and revenue generated such as *The Brie Carre Pizza* can be removed completely from the menu and the resources chanelled to the high performing pizzas or the product can be rebranded and put on promo to improve its sales.

d) For high performing Pizzas such as *The Classic Deluxe Pizza*  and *The Barbecue Chicken Pizza* the ingredient availibility and preparation should always be proritized to avoid going  out of stock.


