# MY-DATA-ANALYSIS-FINAL-PROJECT-ON-EXCEL

This Project is part of my beginner journey into data analysis using microsoft Excel.The dataset used is based on Amazon related data and has been cleaned, analysed, and visualized to extract insights on product listings, prices, rating and more.


## PROJECT TITLE: DATA ANALYSIS CAPSTONE PROJECT
Case Study 1: Amazon Product Review.
analysis

- Project overview

- Analysis Tool

- Dataset Discription

- Dataset cleaning and preparation

- Analysis tasks

### PROJECT OVERVIEW
this is a project that is aimed at analysing product and customer review data to generate insight that can guide product inprovement, marketing strategies, and customer engagements.

### ANALYSIS TOOL
I was requested to use excel to execute 
this project and that is what i used.

### DATASET DISCRIPTION
The dataset contain information scraped from Amazon Product Pages,
including: product details: name, category ,price ,discount, and rating.
Customer engagement: user reviews, titles,and content. .Each role represents 
a unique product,with aggregated reviewer data stored as comma-separated values.

### DATA cleaning AND PREPARATION
Key Steps: The original raw data was cleaned and processed using Excel.

   Remove duplicates and handled missing data
   converted prices, discounts, and review counts into numeric format
   created calculated columns
   such as:
      Total pontential revenue
      Discount-bucket
      Price range bucket
      50% discount or more
      Rating count less than 1000
      
 Total pontential revenue was created by multiplying actual price by
rating count, i did for the first row and used fill handle, 
To further clean the dataset i removed the blank space in some columns by clicking on the dropdown filter and
splitted the category columns.

### ANALYSIS TASKS
Use pivot table and calculated columns where necessary to answer the following:

1. What is the average discount percentage by product category?

To get this, click on a cell in the table, click on pivot table, select new worksheet
and click ok. Drag category volumn into row area and Discount-percentage into values area in the 
pivot table and summarize values by average. click on a cell in the pivot table and do Alt f1 in the keyboard
to present your work in a chart and format to your satisfaction. then ctrl X to cut and Ctrl V to paste in 
the dashboard. Below is the chart representation

![image](https://github.com/user-attachments/assets/e67f941c-5138-4d30-8d2c-a411cefcbbaa)

2. How many product are listed under each category?
   
Duplicate the existing pivot table, unchecked the checked initially, drag category field into rows
product_id field into values area and sumarize value by count. click on a cell in the table, do ALT F1 in the keyboard
to present your work in a chart and format to your satisfaction, CLTR X to cut and CTRL V to paste in the dashboard. 
below is the chart representation

3. What is the total number of review by category

Duplicate the existing pivot table, unchecked the field initially checked, drag category in row area
while rating count field into values area and summarize by sum. click on a cell in the pivot table
Eletronics and Homes & Kitchen have the most products and the highest number of customer reviews, It means they are 
the most active categories.

4. Which product have the highest average rating?

Duplicate the existing pivot table, unchecked initially checked field, drag product_id into rows area while
rating field into values area and summarize by average. click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
![image](https://github.com/user-attachments/assets/8b295801-aa6d-4121-9635-e2138689b960)

5. What is the average actual price vs the discounted price by category?

Duplicate the existing pivot table, unchecked initially checked fields, drag category into rows area, Actual price
and Discounted price field into values area and summarize by average. click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
![image](https://github.com/user-attachments/assets/76c73f13-0f4f-423c-be46-84aa4a8752b4)

6. Which products has the highest number of review?

Duplicate the existing pivot table, unchecked initially checked field, drag product_id field into row, count of rating
field into vales area and summarise by sum.  click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
![image](https://github.com/user-attachments/assets/e9485f91-de21-4f9d-a3e7-bff042642fdf)

7. How many product have a disount of 50% or more?

662 Products has a discount percentage of 50% and more

Duplicate the existing pivot table, unchecked initially checked fields, drag product_id field into row area,
discount_percentage field into vales area and summarize by sum, product-id again into value area and summarize by count. considering the volume of products with 50% discount or more amounting to 662 products.

8. What is the distribution of product ratings?
   
Duplicate the existing pivot table, unchecked initially checked fields, Drag rating field into rows area, product_d 
field into values area and summarize by count to enable you get the number of products per rating.click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
![image](https://github.com/user-attachments/assets/661c902b-dc83-4351-b5c3-7acbf5a228dd)

9. What is the total pontential revenue
(actual_price *rating_count) by category?

Duplicate the existing pivot table, unchecked the initially checked field, drag category column into rows area,
total pontential revenue into values area and summarize by sum.click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
![image](https://github.com/user-attachments/assets/569583e1-f5e2-4399-a15d-8df29d4f107d)

10. What is the number of unique products per price range bucket
(e.g.,<₹200, ₹200-₹500,>₹500)?

Duplicate the existing pivot table, unchecked initially checked field, drag price range field into rows area, price range field into values area and summarize by count.click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
![image](https://github.com/user-attachments/assets/daab1df0-2d52-4222-8955-87a24a33bdd8)

11. How does the rating relate to the level of discount?

This has to do with correlation Analysis
First of all, Duplicate the existing pivot table, unchecked initially checked fields, drag rating field into rows
area, discount percentage field into values area and summarize by average. you will get the table below.

![image](https://github.com/user-attachments/assets/a2525f7f-de66-428b-8aec-82a6a7469e00)

12. How many products have fewer than 1,000 reviews?
All products have fewer than 1000 reviews because the highest review per products is 8.

13. Which categories have products with the highest discount?

duplicate existing pivot table, unchecked initially checked fields, drag product category into rows areas, discount
percentage into values area. click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/c8d78e5d-094c-4b16-ae97-86a679b3db42" />

14. Identify the top 5 products in terms of rating and number of reviews combined.

Duplicate the existing pivot table, unchecked initially checked fields, drag product-id column into rows area, rating column and rating count into values areas and summarize by sum. click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation
<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/e27cfbaf-e8f0-490b-b0f5-6d0990399a7f" />





















