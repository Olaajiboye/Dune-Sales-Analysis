# Exploratory Data Analysis of Dune Sales Performance
## Introduction
Dune is a reputable global retailer offering a diverse selection of products, including accessories, clothing and phones. Dune strives to offer great quality essentials and standout styles that cater to a wide range of customers.
The project focus on analyzing the company’s sales data from the previous year and provide actionable insight	and recommendations. 
## Objective
This analysis will help identify areas of opportunities and inform future business decisions aimed at improving performance and increase profitability.
The project focus on analyzing the company’s sales data from the previous year and provide actionable insight	and recommendations. 
## Tailored Data Analysis
1. calculate cost, Revenue and profit
2. How many customers belong to each customer category
3. How Many transaction by sales person
4. Total Transaction by customer Age group
5. Total Transaction by Customer Gender
6. Total transaction by profilt or loss

## Methodology
The data was analyse using python. I also imported the neccessary library for the Project.
The Library used are Pandas for Data prepprocessing, matplotlib.pyplot for Data Visualization, seaborn for Data Visualization, Counter for counting.
This project is divided into three sections which are: Data Import and Cleaning, Data Analysis and Visualization, Conclusion and Recommendation.

## Data import and Cleaning
 The data type is CSV and was loaded into python using pandas 
 ![Screenshot 2024-01-03 at 10 08 54 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/9f9b41ed-421d-4a27-93fe-61b16429283a)
I also used the data frame to check the rows and coloumns for the first 5 rows in the data table. <br>
For data claening, I checked for missing data and also visualized the missing data. For the data cleaning, the best way to resolved the missing data is to drop the line that is affected with the missing data. <br>
<img width="618" alt="Screenshot 2024-01-03 at 11 10 58 PM" src="https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/cc834871-46c7-4f01-bb14-8e2b5f70aa45"> <br>
<img width="813" alt="Screenshot 2024-01-03 at 11 14 39 PM" src="https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/65772174-d479-4e67-bba6-6feba1aa7297">

## Exploratory Data Analysis
### How many customers belong to each customer category
Customers are categories into 3 major groups which are Low, Medium and High. I then use the seaborn and count to count and visualize how many customer we have in each group.
![Screenshot 2024-01-04 at 7 32 16 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/060e06e0-a945-4b0c-87e5-681fb542f79b)<br>
Result shows we have in the Low Category compared with other categories like medium and high. <br>
### Sales Person - How Many transaction by sales person

![Screenshot 2024-01-04 at 7 35 52 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/fc6c5168-8e78-4e32-9b4f-6b6c93913c8c)
Sales analysis by each saled person shows Remota having the highest sales value and Kenny having the lowest sales value. This analysis can be used to determine the performance of each sales advisor and also as a standard for metrics evaluation.
### Total Transaction by customer Age group


![Screenshot 2024-01-04 at 7 42 14 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/51020384-2e58-49d7-8755-e7c80306b9c4)<br>
I grouped the customer into different 4 age group in order to make it easy to count each transaction with the age group<br>
We have 4 age group which are Young Adult, Adult, Old Adult and Elders based on their age. this is an easy may to view the transaction made in each age group and check the trend from each year. <br>
The analysis and visualization shows more transactions from the adult group who are between the age of 40 and 26 years. This make un understand that our active customers are within this age bracket.

![Screenshot 2024-01-04 at 7 40 35 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/dbc8cf65-52ef-4f66-a03a-ca941a05e735) <br>

### Total Transaction by Customer Gender
The toal transactions by Gender compare in percentage the transaction from Male and Female category. we saw in the visualization that there is more transaction done by Female compare to Male gender. Although the difference is not that much which is around 0.04% 
![Screenshot 2024-01-04 at 8 40 14 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/75c0e1ae-d27b-4576-8d8c-fdc22dec2b4a) 

### Profit and loss analysis from the transaction
The analyis shows that there is Profit generated from all the transaction. we had over 86% Profit mergin from the transaction. we might then look at which product have the hight profit mergin
![Screenshot 2024-01-04 at 8 50 59 PM](https://github.com/Olaajiboye/Dune-Sales-Analysis/assets/152933091/3e6d570b-444b-40f9-9561-e709a26bcb0b)

### Conclusion and Recommendation.
Exploratory Data Analysis (EDA) is an analysis approach that identifies general patterns in the data. These patterns include outliers and features of the data that might be unexpected. 
From the Analysis performed on the Dunes sales performance the company can make informed decision from the analysis of the date. We can see which product is performing well, which staff is perfoming well, what kind of incentive can be use to generate more sales, what type of promotion can drive sales for the company.


