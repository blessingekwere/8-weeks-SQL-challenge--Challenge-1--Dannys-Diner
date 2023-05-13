# Case Study #1 - Danny's Diner

## Introduction

Due to his deep affection for Japanese cuisine, Danny made a heartfelt decision at the start of 2021 to venture into the risky realm of entrepreneurship. He courageously opened a charming, petite restaurant called Danny's Diner, where he wholeheartedly serves his three beloved dishes: sushi, curry, and ramen.
Presently, Danny's Diner requires my invaluable aid as an analyst to ensure its survival. Although the restaurant has managed to gather some fundamental data during its initial months of operation, they are completely clueless about leveraging this data to effectively manage their business. 

*Please Note that this project is first case study of the eight weeks SQL challenge** 
Kindly find full details of the project [here](https://8weeksqlchallenge.com/case-study-1/)

## Problem Statement
Danny is interested in using the data to address a few straightforward inquiries regarding his customers. He specifically wants to understand their visiting patterns, the amount of money they have spent, and their favorite menu items. By establishing a deeper connection with his customers, Danny aims to enhance their experience by providing a more personalized service.

To determine whether expanding the existing customer loyalty program is viable, Danny intends to utilize these insights. Additionally, he requires assistance in creating basic datasets that his team can easily examine without relying on SQL.

Due to privacy concerns, Danny has provided a sample of his overall customer data. He hopes that these examples will be sufficient for you to construct fully functional SQL queries to help him find the answers he seeks.
For this case study, Danny has shared three crucial datasets: sales, menu, and members. You can refer to the entity relationship diagram and example data below to gain a better understanding.

This analysis will answer the following questions using SQL statement.
*	What is the total amount each customer spent at the restaurant?
*	How many days has each customer visited the restaurant?
*	What was the first item from the menu purchased by each customer?
*	What is the most purchased item on the menu and how many times was it purchased by all customers?
*	Which item was the most popular for each customer?
*	Which item was purchased first by the customer after they became a member?
*	Which item was purchased just before the customer became a member?
*	What is the total items and amount spent for each member before they became a member?
*	If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
*	In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?


#### The sales table had the following information
* Customer_id: Unique Identifier of each customer
* Order_date: Date the customer placed an order.
* Product_id: Unique identifier of each product 

#### The menu table had the following information
* Product_id:  Unique identifier of each product 
* Product_name: Name of product
* Price: Cost of product

#### The members table had the following information
* Customer_id: Unique identifier of each customer
* Join_date: Date customer became a member

### Steps Applied
* To start I created a database and named it 'Danny's_Dinner'
* I then created the sales table, followed by the menu table and then the members table using the create table syntax
* I finally inserted the values into each tables using using the 'insert into' syntax

Finally it was time to write queries to answer the business questions...So lets go 

This analysis will answer the following questions using SQL statement.
*	What is the total amount each customer spent at the restaurant?

This query shows that 
Customer A spent $76
Customer B spent $74
Customer C spent $34

*	How many days has each customer visited the restaurant?
This query shows that Customer B visited the restaurant for six days while customer A and C visited 4 and 2 days respectively

*	What was the first item from the menu purchased by each customer?
This query shows that
The first purchase for customer A was sushi and curry.
The first purchase for customer B was curry.
The first purchase for customer C was ramen.

*	What is the most purchased item on the menu and how many times was it purchased by all customers?
This query shows that the most purchased item on the menu is ramen and it was purchased 8 times.

*	Which item was the most popular for each customer?
This query shows that 
The most popular item for customer A was ramen which was purchased 8 times.
The most popular item for customer B was sushi, curry and ramen which was purchased twice each. 
The most popular item for customer C was ramen and it was purchased thrice.

*	Which item was purchased first by the customer after they became a member?
This query shows that Customer A purchased ramen first after membership while customer B purchased sushi first after membership. This means customer C is not yet a member.

*	Which item was purchased just before the customer became a member?
This query shows that 
Before membership customer A purchased curry and sushi 
Before membership customer B purchased sushi

*	What is the total items and amount spent for each member before they became a member?
This query shows that
Customer B spent $40 on three items before membership.
Customer A spent $25 on two items before membership.


*	If each $1 spent equates to 10 points and sushi has a 2x points multiplier - how many points would each customer have?
Customer A will have 860 points.
Customer B will have 940 points.
Customer C will have 360 points.

*	In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi - how many points do customer A and B have at the end of January?
Customer A has 1020 points and customer B has 320 points


## INSIGHTS
From the analysis, we discovered a few but interesting insights that would be certainly useful for Danny.

* Customer B is the most frequent visitor with 6 visits.
* Dannys Diner’s most popular item is ramen, followed by curry and sushi.
* Customer A and C loves ramen whereas Customer B enjoy sushi, curry and ramen equally.
* bCustomer A is the 1st member of Danny’s Diner and his first order is curry.
* The last item ordered by Customers A and B before they became members are sushi and curry.
* Before they became members, both Customers A and B spent $25 and $40.

## RECOMMENDATION
Based on the insights gathered from the data analysis, I would like to make the following recommendations for Danny's Diner:

* Based on the insights gathered, I recommend that Danny’s Diner should focus on promoting their ramen, curry, and sushi menu items to their customers. Since these are the most popular items, highlighting them in marketing campaigns and specials could encourage repeat business from loyal customers and attract new customers.

* Furthermore, since Customer B is the most frequent visitor, Danny’s Diner should consider implementing a loyalty program to reward and retain this customer and other regular customers. By offering rewards, discounts, or free items to repeat customers, Danny’s Diner can create a deeper connection with its customers and incentivize them to visit more frequently.

* Additionally, since both Customers A and B spent a significant amount of money before becoming members, Danny’s Diner should consider offering special promotions or discounts to customers who sign up for the membership program. This could encourage more customers to become members and create a more loyal customer base.

* Finally, since Customer A’s first order was curry and both Customers A and B ordered sushi and curry before becoming members, Danny’s Diner should consider offering more specials and promotions on these menu items to attract new customers and encourage repeat business from existing customers. By leveraging these insights and tailoring marketing efforts accordingly, Danny’s Diner can enhance its customer experience and drive growth in its business.

Thank you! for reading 😊

Kindly connect with me on [Twitter](https://twitter.com/Eddie_Gregs?t=dF3996shVxvPJTePTtxDdw&s=09)
[LinkedIn](https://www.linkedin.com/in/blessing-ekwere-857326216) 
[Medium](https://medium.com/@blessingekwere)
