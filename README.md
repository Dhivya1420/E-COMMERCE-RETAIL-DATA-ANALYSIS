# E-COMMERCE-RETAIL-DATA-ANALYSIS
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/625e64ae-c33a-4244-97ed-f51717daac4d)

Data Preparation and Data Analysis on an ECommerce Data and Finding out the Business Solution for the given Business Objectives.
eCommerce data provides information collected from the eCommerce industry – online retail sites – about products, pricing, sales performance, and customers. Companies with an online retail presence use the data to gain insights into customer behavior and improve their experience. Online businesses and eCommerce retailers leverage eCommerce data to understand how their business performs, carry out competitor analysis, and drive higher online sales.

# TOOL USED: SQL, SQL Server
# DATASET USED: Customers.xlsx, Transactions.xlsx, prod_cat_info.xlsx
# CUSTOMERS:
The file contains the information about customers in the E-Commerce Retail Dataset. It includes variables such as customer_id, DOB, Gender and city_code. Provides SQL queries and scripts for comprehensive customer insights, segmentation, and analytics to drive data-driven business decisions.
**SCHEMA:** The Schema for this Dataset is 4 variable and 5,647 records.

# TRANSACTIONS:
Dedicated to fetching and analyzing transactional data from a comprehensive table. The table encompasses essential fields like such as transaction_id, customer_id, transaction_id, prod_subcat_code, prod_cat_code, quantity, rate, tax, total_amount and store_type. This repository offers SQL queries and scripts tailored for extracting, processing, and interpreting transaction data. It aims to provide valuable insights into customer purchasing behavior, product performance, and financial metrics, enabling businesses to make informed decisions and optimize sales strategies. 
**SCHEMA:** The schema for this Dataset is 10 variables and 23,053 records.

# PRODUCTS:
Retrieving and analyzing data from a product category table. The table includes key information includes variables such as prod_cat_code, prod_cat, prod_sub_cat_code and prod_subcat. This repository offers SQL queries and scripts designed to efficiently fetch and process this data. It aims to provide businesses with insights into product preferences, category trends, and customer purchasing behavior. By leveraging this repository, organizations can better understand their product landscape and tailor their marketing and inventory strategies to meet customer demands effectively.
**SCHEMA:** The schema for this Dataset is 4 variables and 23 records.

# BUSINESS NEEDS:
The primary business objective is to gain insights into customer behavior using point-of-sale (POS) data from our retail store. Through comprehensive data analysis, we aim to uncover purchasing trends, product preferences, and customer segmentation. This analysis will enable us to optimize inventory levels, tailor marketing campaigns, and enhance the overall shopping experience. By understanding customer behavior more deeply, we strive to make informed decisions that drive sales growth, increase profitability, and build stronger relationships with our customers."

# DATA PREPARATION AND UNDERSTANDING:

**(1) The Total number of rows in each table.**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/9739fc72-b650-4bac-9e2a-3d5234acca46)

**RESULT:**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/93ee74d1-87ec-4788-95fc-7bd7c16382c1)

**(2) Number of transactions that have a return**.

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/2d97ce60-48c9-4cc5-a173-2d7b631a369c)

**RESULT:**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/46cf8e2c-b63b-40d2-a270-00507fb85d3e)

**(3) Time range of the transaction data available for analysis.**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/bb1a9f08-4668-4900-a170-7af64cdc9f2b)

**RESULT:**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/0943d9ec-406d-40b8-ad4f-0f0036bb2464)

**(4) The product category does the sub-category DIY belong to**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/8fd7a31b-c342-46b5-bb9b-9ca61e3cd425)

**RESULT:**

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/9634fd8b-d6f2-4c91-a900-4b31502aa09c)

# Business Object 1:
# Which channel is most frequently used for transactions?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/d94ef13d-6b0d-4d6d-b07b-ab18cc3e13e8)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/6da1d4d9-2797-4a29-a6a9-6ac9081a10ea)

# -(Object Result):
According to the result most frequently used channel for Transaction is e_shop and 9311 customers are used the e_shop for their transactions. In this objective count function is used for counting the store_type. Group by and Order by are used for sorting the data. The query identified the store type with the highest number of transactions, providing valuable insights into customer preferences and channel effectiveness.

# Business Object 2:
# What is the count of Male and Female customers in the database?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/82b4fdcb-e194-4d3a-ba0f-e08102f78d00)

# -(Result):

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/d2cd039a-e036-4644-ad81-e30ca2245d13)

# -(Object Result):
"According to the result 2753 female customers and 2892 male customers are in the database. In this objective count function is used for counting the male and female customers. Group by is used for sorting the data. The query grouped customers by gender and counted the number of occurrences for each gender category. Understanding the gender distribution can help the retail store tailor its product offerings, advertising campaigns, and customer engagement initiatives to better resonate with different customer segments, ultimately driving sales and enhancing customer satisfaction."

# Business Object 3:
# From which city do we have the maximum number of customers and how many?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/799d419a-f36d-4497-8d5a-38b7a48ba526)

# -(Result):

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/8d0e293a-7706-4e52-8a27-8aad876f865f)


# -(Object Result):
According to the result city code 3 have the maximum number of customers. There are 595 customers are in city code 3.In this objective count function is used for counting the customers. Group by and Order by are used for sorting the data.It focus marketing efforts, tailor promotions, and optimize inventory to meet the demands of the most populated city.

# Business Object 4:
# How many sub-categories are there under the Books category?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/d2f5fa15-18fd-4bf9-a90b-857678d7244a)

# -(Result):

![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/81a86582-fa03-486f-95c6-c6e105065b42)

# -(Object Result):
The query on 'prod_cat_info' indicates the count of 6 subcategories under the 'books' category.They are Fiction, Academic, Non-Fiction, Children, Comics and DIY. This insight informs inventory and marketing decisions, helping the retail store to diversify and optimize its 'books' product range based on customer preferences and demand. In this objective Where is used for filtering the data and Order by is used for sorting the data.



# Business Object 5:
# What is the maximum quantity of products ever ordered?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/a2947abc-6c2c-48e0-a3fb-99696de1d948)


# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/6da3720c-dde1-4134-aa64-e39272aae85d)


# -(Object Result):
According to the result it provides insights into the distribution of product categories based on the quantity of transactions. This analysis aids in understanding purchasing patterns and helps optimize inventory for different product categories to enhance sales and customer satisfaction.. In this objective count is used for counting the product categories. Inner Join is used for join the two table Transactons and Prod_cat_info. Group by and Order by are used for sorting the data.

# Business Object 6:
# What is the net total revenue generated in categories Electronics and Books?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/8325725b-d024-4183-8eac-e112da32a1e7)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/a4920eae-b844-43b8-a5a9-26f43bc64812)

# -(Object Result):
According to the result the net total revenue generated in categories Electronics and Books are 23545157.6749999. In this objective Sum is used for find the net total revenue. Inner Join is used for join the two table Transactons and Prod_cat_info. Where is used for filter the data. This analysis assists in evaluating the performance of 'electronics' and 'books' segments and guiding targeted marketing and inventory strategies to optimize sales and profitability. 

# Business Object 7:
# How many customers have >10 transactions with us, excluding returns?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/cfe335c1-44d5-4f25-8e24-3f219d4fcb0c)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/ab30a996-780a-4373-ace7-ca384dda134d)

# -(Object Result):
The query identifies 6 customers with more than 10 transactions where the total amount spent is greater than zero. It counts the number of transactions (no_trans_by_customer) for each customer (cust_id) and filters the results to focus on loyal or frequent customers. This analysis provides insights into customer behavior and purchasing frequency, aiding in customer segmentation, targeted marketing, and personalized engagement strategies to enhance customer loyalty and drive sales.

# Business Object 8:
# What is the combined revenue earned from the "Electronics" & "Clothing" categories, from "Flagship stores"?
# -(QUERY): 
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/fa629f42-9c5b-4b07-9217-6e0c2e82bc8f)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/9a9f0362-fb67-417a-a944-64f0681167fb)

# -(Object Result):
The query calculates the result 3409559.27000001 is the combined revenue earned from the "Electronics "and "Clothing"categories from "Flagship store". By joining 'Transactions' with 'prod_cat_info' based on matching product category codes, it provides insights into revenue generated from these categories at flagship stores. This analysis assists in evaluating the performance of specific product categories at flagship locations, guiding inventory management and promotional strategies to optimize sales and profitability.

# Business Object 9:
# What is the total revenue generated from "Male" customers in "Electronics" category? Output should display total revenue by prod sub-cat.
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/0917e894-58b4-4fb7-b669-775209041a67)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/76127b3b-812a-4c6c-98dd-b519a2bbc104)

# -(Object Result):
According to the result 10947130.025 is the total revenue generated from "Male" customers in "Electronic" and total revenue by prod sub categories such us Personal Appliances, Mobiles, Computers, Audio and video and Camera of each category is 5703109.42500002. In this objective Sum is used for find the total revenue. Inner Join is used for join the two table Transactons and Customers. Where is used for filter the data.This analysis helps in understanding male purchasing behavior in the electronics category, guiding targeted marketing campaigns and inventory strategies to cater to this specific customer segment and optimize sales.

# Business Object 10:
# What is percentage of sales and returns by product sub category; display only top 5 sub categories in terms of sales?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/ffabd43b-709f-481f-af9c-53ad02d2af8c)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/f35b9d82-7ab6-43f3-903f-a9b7cd9c66d1)


# -(Object Result):
According to the result we get top 5 percentage of sale and returns by product sub category such as Women, Mens, Comics, Children and Academic. In this objective CTEs are used for finding the solution. inner Join is used for join the two table Transactons and Prod_cat_info. Where is used for filtering the data. Group by and Order by are used for sorting the data. This analysis offers insights into the best-performing product subcategories, guiding inventory management, marketing strategies, and product promotions to optimize sales and enhance profitability.

# Business Object 11:
# For all customers aged between 25 to 35 years find what is the net total revenue generated by these consumers in last 30 days of transactions from max transaction date available in the data?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/47c5fa72-1976-4697-9d4b-3de28bd5d373)


# -(Result): 
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/f67b73e2-da70-4b36-a5ef-23868903772c)

# -(Object Result):
According to the result the net total revenue generated by customers age between 25 to 35 years are 211997.565. In this objective CTEs are used for finding the solution. inner Join is used for join the two table Transactons and Customers. Where is used for filtering the data. Group by and Order by are used for sorting the data. This analysis assists in understanding the spending behavior of young to middle-aged customers, guiding targeted marketing and promotional strategies to optimize sales and customer engagement.

# Business Object 12:
# Which product category has seen the max value of returns in the last 3 months of transactions??
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/7f0282fe-4687-49d8-9577-5ca69fd8b44b)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/b0a29341-060f-4fee-bf81-96398cccbfa6)

# -(Object Result):
According to the result Home and kitchen has seen the maximum value of returns in the last 3 months of transactions. In this objective inner Join is used for join the two table Transactons and Prod_cat_info. Where is used for filtering the data. Group by used for sorting the data.This analysis provides insights into return rates for different product categories during the specified period, helping to identify potential issues with product quality, customer satisfaction, or inventory management that may require attention and optimization strategies to reduce returns and enhance profitability.

# Business Object 13:
# Which store-type sells the maximum products; by value of sales amount and by quantity sold?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/1121f7c8-7b79-4053-9572-63091d5dc7e3)


# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/d26c0ca4-501e-41ce-a071-6e640654cbf0)

# -(Object Result):
According to the result store_type e-Shop sells the maximum products by 22185609.8749999 sales amount and 8429 quantity sold. In this objective count is used for counting the quantity sold and Sum is used for find the amount. Where is used for filtering the data. Group by and Order by are used for sorting the data. This analysis offers insights into the performance of different store types in terms of sales volume and revenue, guiding strategies to optimize sales, inventory management, and promotional activities to drive profitability and business growth.

# Business Object 14:
# What are the categories for which average revenue is above the overall average?
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/ee1c7e9f-b170-4a5a-8689-29b2af4a5d4d)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/770cdd0d-0437-409f-afa7-f171133a5346)

# -(Object Result):
According to the result Books, Clothing, Electronics are the 3 categories for which average revenue is above the overall average. In this objective inner Join is used for join the two table Transactons and Prod_cat_info. Having is used for filtering the data. Group by used for sorting the data. This analysis identifies product categories that perform above the average, providing insights to focus on high-performing categories for inventory management, marketing strategies, and promotional activities to optimize sales and profitability.

# Business Object 15:
# Find the average and total revenue by each subcategory for the categories which are among top 5 categories in terms of quantity sold.
# -(QUERY):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/940397b8-b163-4b52-b35f-95f496ac30b7)

# -(Result):
![image](https://github.com/Dhivya1420/E-COMMERCE-RETAIL-DATA-ANALYSIS/assets/164134417/ea167f4f-85e7-4d5a-8ab8-f7c0eab5ecd5)

# -(Object Result):
According to the result we get the average and total revenue by each subcategory for the categories which are among top 5 categories. In this objective inner Join is used for join the two table Transactons and Prod_cat_info. Control flow function Case is used for finding the data. Where is used for filtering the data. Group by and Order by used for sorting the data.

# RECOMMENDATIONS:
Based on the previous result, here are some recommendations for the business:

# INVENTORY MANAGEMENT: 
Prioritize stocking and replenishing the top 5 best-selling product categories to ensure product availability and meet customer demand effectively.

# MARKETING STRATEGIES: 
Allocate a higher marketing budget and promotional efforts towards the identified top-performing product categories to capitalize on their popularity and drive sales.

# PRODUCT BUNDLING: 
Consider creating product bundles or packages incorporating items from the top-selling categories to encourage higher sales and increase average transaction value.

# CUSTOMER ENGAGEMENT:
Develop targeted marketing campaigns and personalized promotions for the top-selling product categories to engage customers and enhance their shopping experience.

# SUPPLIER NEGOTIATION:
Negotiate better terms with suppliers for the top-performing product categories to improve profit margins and reduce costs.

# INVENTORY ANALYSIS: 
Conduct a detailed inventory analysis to identify slow-moving items in other categories and consider reevaluating their placement, pricing, or promotion strategies to boost sales.

# CROSS-SELLING OPPORTUNITIES:
Explore cross-selling opportunities by recommending products from the top-performing categories to customers purchasing items from other categories to increase average transaction value.

By implementing these recommendations, the business can optimize its sales strategies, improve inventory turnover, enhance customer satisfaction, and ultimately drive profitability and growth.

# CONCLUSION:
By exploring various aspects of the dataset, a comprehensive understanding of E-Commerce Retail area. The analysis shows the various aspects of customers and the trends.The analysis revealed the most popular products and the revenue of the products. Most frequently used channel for Transaction is e_shop and This information can assist other channel to improve their area and make customer choice. Home and kitchen product category has seen the maximum value of returns in the last 3 months of transactions and it shows the customers interest in this product. It increase the marketing and growth of the product.Analysis shows the growth in sales revenue over the past years. our e-commerce retail data analysis has provided valuable insights that can inform strategic decision-making and drive business growth. By these insights and recommendations, we are poised to enhance the customer experience, optimize marketing efforts, and maximize revenue potential. We Utilized Comman Table Expressions(CTE), AggregationFunctions (eg: SUM,AVG) and Local Operations to extract insights such as Total revenue, Top-selling categories, and Customer behavior patterns.
