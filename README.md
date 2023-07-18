# EDA in Superstore Sales Analysis

This is an EDA project to analyze the sales in Superstore in the USA.

# Purpose

The purpose of this analysis is to understand the business situation of Superstore in the USA from 2014-2017 in the USA. The insights gained from this analysis will back up the idea that maximizing the sales and profit of the company. Moreover, this case study will also analyze the behaviors and patterns of customers. The result of this analysis will provide some ideas for the marketing strategy. 

# Metadata
* Row ID => Unique ID for each row.
* Order ID => Unique Order ID for each Customer.
* Order Date => Order Date of the product.
* Ship Date => Shipping Date of the Product.
* Ship Mode=> Shipping Mode specified by the Customer.
* Customer ID => Unique ID to identify each Customer.
* Customer Name => Name of the Customer.
* Segment => The segment where the Customer belongs.
* Country => Country of residence of the Customer.
* City => City of residence of the Customer.
* State => State of residence of the Customer.
* Postal Code => Postal Code of every Customer.
* Region => Region where the Customer belongs.
* Product ID => Unique ID of the Product.
* Category => Category of the product ordered.
* Sub-Category => Sub-Category of the product ordered.
* Product Name => Name of the Product
* Sales => Sales of the Product.
* Quantity => Quantity of the Product.
* Discount => Discount provided.
* Profit => Profit/Loss incurred.

# Data 

The data was collected based on the provided link [https://divvy-tripdata.s3.amazonaws.com/index.html](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). The data from the period of 4 years from 2017-2015 was selected for the analytic. There are a total of 9,994 data points in this dataset. 
  
# Tools: Python, MySQL, and Power BI

In this case study, the data will be loaded into MySQL local server. Many basic analyses and cleaning data were done through Python. The cleaning and data modeling was done with Python. Visualization steps were done through the business intelligence tool called Power BI. 

![ERD](https://github.com/JackLieu95/Sales-Analysis/assets/85127821/c3bfe333-2f22-4f43-b956-2e0a35497cc8)

# Result:
![Untitled](https://github.com/JackLieu95/Sales-Analysis/assets/85127821/28cb1593-3812-4908-942c-2e788fcf1ebf)

* The total Sales for the 4-year period were 2.30 million while the profit was around 286.40 thousand with approximately 38 thousand items sold.
* The total Sales and profit increased during the period of 4 years where the West and the East account for the largest sales which were 725.46 thousand and 678.78 thousand, respectively.
* There was a slight difference in Sales and Profit between States. The top 3 States which had the largest Sales were: California, New York, and Texas while the top 3 in Profit were: California, New York, and Washington. The 10 top best-selling cities are NYC, LA, Seattle, Philadelphia, San Francisco, Chicago, Houston, Jackson Ville, Springfield And San Diego. These states should be the key points for the marketing strategies due to the volume of customers. There should be more promotion plans to be operated in these locations to attract more customers.
* According to data, The last quarter seemed to be the time when the store is busiest. Though, There was a trend that customer was likely to shop in the first quarter for years. The company should be prepared for this period to be able to meet the customer needs, such as: hiring casual employees, stocking products before this time, and preparing more vehicles for delivery.
* As can be seen on the dashboard, there was a big difference between Sales and Profit according to categories. While there was not much difference in Sales between technologies, office supplies, and furniture, the furniture had the least profit compared to the others. Moreover, there was a trend where the profit from technologies and office supplies were increasing during the period while furniture was decreasing. Their company should investigate closer with the price as well as the promotion plan for furniture products.
* The consumers accounted for the most sales during the period followed by the cooperating and home office. Between the top 10 sales cities, only Florida and Illinois had the sales of home offices bigger than cooperates. Therefore, the promotion strategies for consumers and the home office should be more focused on these 2 cities.
* The average delivery time was 4 days. The total number of transaction which was delivered in less than 4 days was very limited. Therefore, The company should increase the ability of delivery to enhance customer satisfaction.
* Phones, chairs, and storage were the top 3 most selling while copiers, phones, and accessories were the top 3 most profitable products. So, the company should focus on products of these subcategories to optimize the profit instead of selling. 

# Recommendation for further analysis:

* This analysis can be extended by collecting more information about the customer such as age, sex, salary range, or address. These factors can help draw a more details picture of customer behavior. 
* Moreover, with more data points about the customers, the machine learning model can be applied to identify the factors that affect to the decision of using service of customers. 
