# MY-DATA-ANALYSIS-FINAL-PROJECT-ON-EXCEL

This is a project executed at the end of my data analysis course under the guidance of Digital Skill Up Africa.


## PROJECT TITLE: DATA ANALYSIS CAPSTONE PROJECT
Case Study 1: Amazon Product Review.
analysis

- Project overview

- Analysis Tool

- Dataset Discription

- Dataset wrangling and preparation

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

### DATA WRANGLING AND PREPARATION
First of all, read the instrutions and requirement given meticuulously
as this will enable you ascertain what is necessary and what is not.

Having read through thoroughly, i opened the Excel data to commence the cleaning by
removing duplicate rows that are not necessary for the analysis i intend to conduct.

I created a column, new column for main category, considering the fact that i noticed
there are repitition in the content ans separated by a pipe "|" symbol. others column created are S\N 
which was created by specifying a pattern by typing the firdt two numbers and use the fill handle
to automatically fill others. Total pontential revenue was created by multiplying actual price by
rating count, i did for the first row and used fill handle, 
To further clean the dataset i removed the blank space in some columns by clicking on the dropdown filter and
splitted the category columns

At this point i copied all the columns into another sheet.

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

![image](https://github.com/user-attachments/assets/a908fd52-894e-478a-b778-e89acf69a115)

3. What is the total number of review by category

Duplicate the existing pivot table, unchecked the field initially checked, drag category in row area
while rating count field into values area and summarize by sum. click on a cell in the pivot table, do ALT F1
to present your work in a chart, and format to satisfaction. CTRL X to cut and CTRL V to paste in the dashboard
below is the chart representation
![image](https://github.com/user-attachments/assets/1fe34e58-d80f-4ee5-8c06-79159484883c)

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

Duplicate the existing pivot table, unchecked initially checed fields, drag product_id field into row area,
discount_percentage field into vales area and summarize by sum.click a cell in the pivot table do ALT F1 to present your work in a chart and format to satisfaction. CTLR X to cut and CTL V to paste in the dashboard.
below is the chart representation














