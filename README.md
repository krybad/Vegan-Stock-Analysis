# Vegan-Stock-Analysis
Semester Project in Data Warehouse and Data Lake Systems 2 (https://www.hslu.ch/en/lucerne-school-of-business/degree-programmes/master/applied-information-and-data-science/) 

## Introduction
Vegan products are getting more popular each year and revenues grow rapidly. As a result, stocks of vegan-focused producers enter the big stage of the stock market. It's a new industry with limited information in the stock market. We aim to find alternatives to traditional technical stock trading indicators. First, an architecture with a Postgresql DB Datalake and a Postgresql DWH is built where AWS Lambda functions push data into the DL and the DWH. Data analysis with Correlation Analysis is used to observe the relations between twitter data and stock price movements of vegan stocks. However, it's just an Draft which has to be optimized to use in a real-life use case. 

Research Questions: 
1. Does the stock price of a vegan stock* increase, in case tweet mentions of the word "vegan" increases?
2. Does the stock price of a vegan stock* increase, in case the positive tweet sentiment of tweets including the word "vegan" increases? 

*Vegan stocks: 
- Beyond Meat
- The Tattooed Chef
- The Very Good Food Company
- Oatly
- Kellogs (Big player with some vegan products)

## Architecture
AWS Services have been used as well as Tableau. The picture below shows the architecture. Some services are not on the picture such as AWS Eventbridge or AWS Cloud9 we have used. 
![image](https://user-images.githubusercontent.com/82529419/149653491-9471c84c-4312-41f2-ba36-4f0a1ea0c250.png)
