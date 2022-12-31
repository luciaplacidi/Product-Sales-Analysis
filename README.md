# Product Sales Analysis and Visualization

## About the Data
The analysis was based on a dataset from Pomerol Data Challenge for December 2022 challenge. The goal for this analysis is to
find which products are selling the most, making the most sales and which cities generate the most revenue.

The dataset contains 12 monthly csv tables with a total of 186,845 records. It includes Order ID, Product, Quantity Ordered, Price and Purchase Address.

Objective:

1: What was the best month for sales? How much was earned that month? 

2: What City had the highest number of sales? 

3: What time should we display advertisement to maximize likelihood of customer’s buying product? 

4: What product sold the most? Why do you think it sold the most? 


## Data Prep and Analysis
* Appended monthly datasets into a new dataset.
* Removed errors and blanks.
* Split order date column by dleimiter into 2 columns “Date” and “Time”.
* Split address column into address, city, state, zip code.
* Created a column to calculate revenue / sales.
* Created a column to calculate order time to nearest hour.
* Created a measure for monthly average sales.

## Key Findings
* Total sales for the year was $34,492,036.
* December had the highest sales. This could be due to the increased spending during the holiday period.
* The product that made the most sales was the MacBook Pro laptop.
* The product that was ordered the most was AAA Batteries (4-pack).
* San Francisco was their highest-performing city. California was their highest performing state.
* To maximize the likelihood of customer's buying products, advertisements should be displayed late mornings and late afternoons as most orders were made midday and late at night.

## Visualization
Power BI [link](https://app.powerbi.com/links/C944D12UjP?ctid=3c71cbab-b5ed-4f3b-ac0d-95509d6c0e93&pbi_source=linkShare)

![Product Sales Analysis](https://user-images.githubusercontent.com/119815423/210156173-465d7bdc-72f8-441d-84f3-cbe20ff76c64.jpg)
