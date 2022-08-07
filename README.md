# E-Commerce-Data-Analysis-and-Visulization---Olist

## About Project 
Performed company, customer, product, and metrics analysis and visulization for Brazilian E-Commerce company

Conducted ETL using MySQL, including extracting, cleaning, and analyzing data.

Developed a Tableau dashboard to produce quantitative and intuitive visualizations of valuable insights and further provide business recommendations.


## Data Source: 
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Technologies Used:
1. MySQL
2. Tableau
3. Jupyter Notebook

## Project Planning 
1. Motivation
    1. To unlock its early-stage sales and operation since its inception in 2015
    2. To gain in-depth understanding of e-commerce database, business, metrics, and analysis methods
2. Stakeholders: Strategy manager, Sales department, Customer service team, I.T Team
3. Output
    1. An informative and intuitive dashboard that delivers valuable insights for decision makers.

## Setup Process
1. Install all technologies 
2. Construct Database in MySQL (See Build_databse.sql)

## Detailed Approaches
**1. Data Prepossessing & Cleaning**
* Data Deduplication
* Missing Value 
* Abnormality Check
   * Compared with 2017 and 2018, the data at the end of 2016 is missing or abnormally small

**2. Data Analysis Using MySQL**
*  GMV_&_Sales_Insight.sql: Developed a quick overview and trend analysis of Olist’s sales, transactions, GMV, and average order value (AOV) from 2017.01 to 2018.08
*  Customer_Analysis.sql: Performed general customer analysis such as spending, growth, and retention, while deep diving into core customers’ behavior and preference
*  RFM_Segmentation.sql: Scored recency, frequency, and monetary value for each customer, and implemented RFM customer segmentation
*  Product_Analysis.sql: Developed a product analysis such as purchase delivery process, the most popular product category and the transaction trend

## Visualization & Key Insights

<img width="600" alt="overview" src="https://user-images.githubusercontent.com/88640967/183311427-98382c5c-072d-43a4-a41e-777fbcafdf7a.png">

* State “SP” was the most important contributor to GMV ( ~37%)
* GMV surged in 2017.11 (holiday effect)
  
<img width="600" alt="customer" src="https://user-images.githubusercontent.com/88640967/183311442-08376a46-a5a5-4d06-8dba-2ba76f5b6da4.png">

* Olist was very popular in the southeast of Brazil, especially the State ‘SP’. 
* Since Olist was in the early stage, they had high growth and high churn in customers.

<img width="600" alt="core" src="https://user-images.githubusercontent.com/88640967/183311449-14fa9875-473d-4d22-be33-f31348ede0cf.png">

* Most of the core customers prefer to place orders during weekdays, especially Monday and Wednesday. During weekends, on the contrary, seldom do core customers make transactions. 
* A large percentage of customers placed only one order, about 3000 customers placed up to 4 orders. The maximum orders placed per customer is 17. 
* 73.14% of customers made their transactions using credit cards, only 1.21% of customers purchased using debit card.
* The top 2 spending distributions of core customers are spendings between $100 to $500 (49.13%), and spendings below $100 (46.21%).

<img width="600" alt="rfm" src="https://user-images.githubusercontent.com/88640967/183311531-42889893-c5e8-410c-8d33-b9a055390b6d.png">

* The 3 biggest customer groups of Olist are "Regular Customers", "Recent Customers", and "Need-Attention Big Spenders", and it lacked loyal customers and super fans.

<img width="600" alt="product" src="https://user-images.githubusercontent.com/88640967/183311454-78310f8d-5c02-4df2-b180-b8a3ecfb8d38.png">

* Bes_bath_table is the top 1 sales category with most “recomendo” in comments
* On average, after a customer placed an order, they need around 24 days to receive the product.

<img width="600" alt="product_1" src="https://user-images.githubusercontent.com/88640967/183311507-1f54c9d0-820b-43a3-9705-4aad61814cf0.png">

* Health beauty has top 5 sales and  a growth trend, which shows its potential
* Sports_leisure has top sales, but shows a decreasing trend, and it has the most canceled orders around all product categories, which is a warning sign

## Conclusion and Recommendations
* In 2017-2018, Olist showed growth but serious geological inequality in its GMV, so that it could boost growth and attract more customers in other areas (through holiday promotions or campaigns) while keeping their popularity in the southeast.
* With the high growth and high churn of customers, Olist should cultivate more loyal customers through deep diving into core customer’s behavior and preference (Ex. such as new product reminder and promotion in weekday, credit card encouragement, loyal program, personalized ads/emails, etc)
* With over 112k products, Olist should focus more on potential product categories (ex. Bed_bath_table, health_beauty), and figuring out why some categories (ex. Sport leisure) are not or no longer popular.
* In terms of satisfaction, Olist could improve their distribution, delivery, and after-sales questionnaire and service, in order to give customers a better shopping experience, and then shop more frequently and boost revenue.


