
**INTRODUCTION:**
Supermarket data analysis is the process of examining the vast amount of data collected by supermarkets to gain insights into customer behavior, optimize operations, and improve profitability. By leveraging advanced analytics and data science, supermarkets can make data-driven decisions, personalize marketing strategies, and enhance the overall shopping experience. In this guide, we will delve into the various facets of supermarket data analysis, exploring its importance in today's competitive retail landscape.


**DATASET OVERVIEW:**
The dataset comprises a comprehensive collection of attributes that capture the essence of supermarket sales, ranging from customer demographics to product details. These attributes include branch identifiers, city locations, customer types, gender distributions,
product categories, unit prices, quantities purchased, Tax 5%, total sales amounts, time, payment methods, cogs, gross income and customer ratings.
The Supermarket sales data from the Kaggle dataset.
Throughout this project, we employ various data visualization techniques to uncover hidden trends, relationships, and anomalies within the data. Our analytical journey is divided into three types- 
**Univariate Data Analysis:** Single variable Analysis
**Bivariate Data Analysis:** Two variable Analysis
**Multivariate Data Analysis:** More than two variable Analysis


**FAMILIARIZE WITH THE DATASET AND VARIABLES:**
The dataset consists of historical sales data of a supermarket company from 3 different branches over **3 months** from **Jan-March 2019**. 
The dataset consists of data from 3 cities or 3 branches in **Myanmar** are:

**Branch A(Yangon)**

**Branch B(Mandalay)**

**Branch C(Naypyitaw)**

Following table provides a summary of the columns and the columns description:

**S.NO
Column Name
Column Description**

**Branch:**
Branch of Supermarket(3 branches are available identified by A, B and C)

**City:**
Location of Supermarket

**Customer Type:**
Types of Customers, recorded by Members for customers using member card and Normal for without member card

**Gender:**
Gender types of Customers(Male/Female)

**Product Line:**
General item categorization groups- Electronic accessories, Fashion accessories, Food and beverages, Health and Beauty, Home and lifestyle, Sports and travel

**Unit Price:**
Price of each product in $

**Quantity:**
Number of products purchased by customer

**Tax:**
5% tax free for customer buying

**Total:**
Total Price including tax

**Time:**
Purchase time(10am to 9pm)

**Payment:**
Payment used by Customer for purchase(3 methods are available- Cash, Credit card and E-wallet)

**COGS:**
Cost of Goods Sold

**Gross income:**
Gross income from Customers i.e. income of supermarket and spend b customers

**Rating:**
Customer stratification rating on their overall shopping experience(On a scale 1 to 10, 1 being lowest and 10 being highest)



**FINAL CONCLUSION:** 
In conclusion, some of the findings or Observations from the Supermarket Sales Dataset:
The customer rating is more or less uniform with the mean rating being around 7 and there is no relationship between gross income and customer ratings.
The data consists of 3 cities/branches. Though branch A has slightly higher sales than the rest, C i.e. Naypyitaw is the most profitable branch in terms of gross income.
Fashion accessories and food and beverages are the most sold product in Naypyitaw and these products should be focused on along with electronic accessories.
The most popular payment method is E-wallet and cash payment is also on the higher side.
There is no particular time trend that can be observed in gross income.
At an overall level,’Sports and Travel’ generates the highest gross income.
Gross income is similar for both male and female, though female customers spend a bit higher at the 75th percentile. Females spend on ‘Fashion accessories’ the most and for males surprisingly it is ‘Health and beauty’. Females also spend more on ‘Sports and travel’ which generates the highest income overall.
Using the correlation analysis, one interesting observation has emerged that customer ratings are not related to any variable.
Most of the customers buy 10 quantities and the busiest time of the day is afternoon i.e. around 2 pm which records highest sales. 
Though the rating for ‘fashion accessories’ and ‘food and beverages’ is high, the quantity purchased is low. Hence, supply for these products need to be increased. 

