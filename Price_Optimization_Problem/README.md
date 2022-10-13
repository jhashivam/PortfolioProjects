# ML Project for Retail Price Optimization

### Description : 
Pricing a product is a crucial aspect of any business. A lot of thought process is put into it. There are different strategies to estimate prices for different kinds of products. There are products whose sales are pretty sensitive to their costs, and as such, a slight change in their price can lead to a noticeable difference in their sales. At the same time, there are also products whose sales are not much affected by their worth - these tend to be luxury items or necessities (like certain medicines). 
Price elasticity of demand (EPD), or elasticity, is the degree to which the compelling desire for something changes as its price changes. In general, people desire things less as those things become more expensive. However, for some products, the customers’ desire could drop sharply even with a bit of price increase, and for other products, it could stay almost the same even with a hefty price increase. Economists use the term elasticity to denote this sensitivity of sales to price fluctuations. More precisely, price elasticity gives the percentage change in quantity demanded when there is a one percent increase in price, holding everything else constant.

### Retail Price Optimization using Python
In this machine learning pricing optimization project, we will take the data of a cafe and, based on their past sales, identify the optimal prices for their items based on the price elasticity of the items. First, you will calculate the price elasticity for each item, then figure out the optimal price. While taking a particular cafe data, we can extend this work to price any product. This machine learning retail price optimization project will focus on the former products.

![RPO-01](https://github.com/jhashivam/PortfolioProjects/blob/main/Price_Optimization_Problem/RPO-snap/RPO-01.png)

### Dynamic Pricing Dataset
The data is contained in three CSV files.
1. **Cafe - Sell MetaData.csv** This file has details about sales made by the cafe.
    - Columns: 
    `*Sell ID, Sell Category, Item ID, Item Name`
2. **Cafe - Transaction - Store.csv** This file contains information about transactions and sale receipts of the cafe.
    - Columns:
    `*Calendar Date, Price, Quantity, Sell ID, Sell Category*`
3. **Cafe - DateInfo.csv** This has date information corresponding to the transactions performed.
    - Columns: 
    `*Date, Year, Holiday, Weekend, School Break, Temperature, Outdoor*`


### Tools and techniques used in this project

#### Price Optimization Algorithms
Understanding customer behavior through sales data is crucial for the growth of any business. Not only it contributes to improved quality of products, but it additionally assists in determining the right price for the different products. For instance, products perceived as luxury items by the masses are sold at unreasonably high prices. In this dynamic pricing python project, you will use previous sales data to estimate the cost of different food items in a cafe. Additionally, you will learn about other price optimization methods like cost-less pricing, competition-based pricing, perceived value pricing, and demand-based pricing. This project will also introduce you to price elasticity, a concept that plays a critical role in determining price estimates.
 
#### Exploratory Data Analysis
Before the price optimization dataset is used for modeling, it must be processed. The dataset may contain redundancy that one must remove, and one must bring on all the variables of different data types on the same foot. In this project, you will work on the dataset of a burger cafe and use their three datasets related to sales, transactions, and corresponding dates. You will learn how to analyze the dataset using data visualization libraries of Python: matplotlib and seaborn. This price optimization machine learning project will also guide you on merging the datasets and preparing them to apply machine learning algorithms using Pandas dataframes.
 
#### Machine Learning Algorithms
Instead of traditional statistical methods of price estimation, this project will perform price optimization using machine learning in Python. You will learn how to use the regression trees and ordinary least square method to estimate the price elasticity for different products. Furthermore, you will understand how statistical parameters like the r-squared value are interpreted for analysis. The project will also teach you how to improve the accuracy of the models by eliminating specific variable values. Additionally, you will explore maximizing profit using the results of price elasticities evaluation.
 
#### Application of ML for Pricing Optimization in Python Project
Primarily, this project focuses on optimizing the prices of various items available in a burger cafe. The solution of this pricing optimization in Python project can be easily used by experts of different industries like medical, hospitality, insurance, etc. For example, an analyst can recommend changes to the prices of various services offered by a hotel depending on the previous residents’ feedback.


### FAQs for Pricing Optimization with Machine Learning
##### 1) How do you do Price Optimization?
We can apply different types of price optimization techniques like reducing cannibalization for inter and intra products of the same company, reducing cost drastically while playing a volume game etc.   
##### 2) What is Price Optimization Machine learning?
Price Optimization can be achieved using regression machine learning algorithms like linear regression. One can first estimate the price elasticity for each product using the past sales data and then use that coefficient for price optimization.



### Note-

1. Price elasticity - Price elasticity of demand is a measurement of the change in the consumption of a product in relation to a change in its price. Expressed mathematically, it is:
Price Elasticity of Demand = Percentage Change in Quantity Demanded / Percentage Change in Price

                                                  𝑒=%Δ𝑄/%Δ𝑃

![RPO-02](https://github.com/jhashivam/PortfolioProjects/blob/main/Price_Optimization_Problem/RPO-snap/RPO-02.jpeg)