# EDA in Superstore Sales Analysis

This is an EDA project to analyse the sales in Superstore in USA.

# Purpose

The purpose of this analysis is to understand the business situation of Superstore in USA from 2014-2017 in USA. The insights gained from this analysis will back up the idea that the maximizing the sales and profit to the company. Moreover, this case study will also analyze the behaviors and pattern of customers. The result from this analysis will provide some ideas for the marketing strategy. 

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
* City => City of residence of of the Customer.
* State => State of residence of the Customer.
* Postal Code => Postal Code of every Customer.
* Region => Region where the Customer belong.
* Product ID => Unique ID of the Product.
* Category => Category of the product ordered.
* Sub-Category => Sub-Category of the product ordered.
* Product Name => Name of the Product
* Sales => Sales of the Product.
* Quantity => Quantity of the Product.
* Discount => Discount provided.
* Profit => Profit/Loss incurred.

# Data 

The data was collected based on the provided link [https://divvy-tripdata.s3.amazonaws.com/index.html](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). The data from period of 4 years from 2017-2015 was selected for the analytic. There are totally 9,994 data points in this dataset. 
  
# Tools: Python, MySQL and Power BI

In this case study, the data will be loaded into MySQL local sever. Many basic analysis and cleaning data were done through Python. The cleaning and data modeling were done with Python. Visualization steps were done through the business intelligence tool called Power BI. 

![ERD](https://github.com/JackLieu95/Sales-Analysis/assets/85127821/c3bfe333-2f22-4f43-b956-2e0a35497cc8)

# Result:
* The total Sales for the 4 year period was 2.30 million while the profit was around 286.40 thoundsand with approximate 38 thousand items were sold.
* The total Sales and profit had increased druring the period of 4 years where the West and the East accounte for the largest sales which were 725.46 thousand and 678.78 thousand, respectively.
* There were a slightly diffrent in Sales and Profit between States. The top 3 States which had the largest Sales were: California, New York, and Texas while the top 3 in Profit were: California, New York, and Washington. The 10 top best selling cities are: NYC, LA, Seattle, Philadelphia, San Francisco, Chicago, Houston, Jackson Ville, Springfield And San Diego. These states should be the key points for the marketing strategies due to the volumns of customer. There should be more promotion plan to be operated on these locations to attract more customers.
* According to data, The last quater seemed to be the time where the store is busiest. Though, There was a trend that customer was likely to shop at the first quater during for years. The company should be prepare for these period in able to meet the customer needs, such as: hiring for casual employees, stocking products before this time and prearing more vehicles for delivering.
* As can be seen on the dashboard, there was a big difference between Sales and Profit according to categories. While there were not much different in Sales between technologies, office supplies and furniture, the furniture had the least profit comparing to the others. Moreover, there was a trend where the profit of technologies and pffice suppllies were incresing during the period while furnitures was decreasing. There comapny should investigate closer with the price as well as the promotion plan for furniture products.
* The consumers accounted for the most sales during the period follow by the cooperate and home office. Between the top 10 sales cities, only Florida and Illinois had the sales of home offfice bigger than coopertes.Therefore, the promotion strategies for comsumer and home office should be more focus on these 2 cities.
* The average of delivery time was 4 days. The total number of transaction which was delivery less than 4 days was very limited. Therefore, The company should incereased the ability of delivery to enhance the customer satisfaction.
* Phone, chair and storage were the top 3 most selling while copiers, phones and accessories were the top 3 most profit products. So, the company should be focus on products of these sub catrgories to optimize the profit in stead of selling. 

# Recommendation for further analysis:

* This analysis can be extended by collecting more information about the customer such as age, sex, salary range, or address. These factors can help draw a more details picture about the customer behavior. 
* Moreover, with more data points about the customers, the machine learning model can be applied to identify the factors that affect to the decision of using service of customers. 
