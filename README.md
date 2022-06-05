# DSND-Writing-a-Data-Scientist-Blog-Post

## Motivation for the project

Gas prices have been fluctuating rapidly all over the world. Some goverments are proposing solutions like tax break, etc, to curb the effects of high gas prices. With this project, I am intereseted in knowing how much of the gas prices paid by customers end up with the government. I am interested in finding out the relationship between various types of taxes related to gasoline in the USA.

Having a clear idea on how much goes where can help me answer the following questions:

1. Which states in the USA are most and least expensive in terms of gasoline prices?

2. What are the types of taxes paid on gasoline and how much are these taxes in various states in the USA?

3. What are the factors affecting gas prices along with their respective shares?

A medium article was published with the results of this analysis, here's the link to the article: 

https://medium.com/@ygsingh101/what-is-driving-the-gas-prices-in-the-usa-ff915aefe6d5

## Libraries Used
1. urllib
2. requests
3. BeautifulSoup
4. pandas
5. numpy
6. matplotlib

## Files

├── data  
│   ├── fuel_data.csv   
│   ├── fueltaxes.xls   
│   ├── state_areas.csv   
│   ├── state_code.csv   
│   ├── state_fuelprice.csv   
│   ├── state_gasrate.csv   
│   ├── state_gastax.csv   
│   ├── state_latlong.csv   
│   ├── state_pop_area.csv   
│   ├── state_population.csv   
│   └── state_salestax.csv   
├── README.md   
├── scrape_website.ipynb   
└── Write a Data Science Blog - Data Preparation.ipynb   

## Results Summary
1. We found that the state with most expensive gas in the USA is California and the least expensive gas is Oklahoma.
2. We then found out the state with most tax on gasoline sale is California and the least tax is Alaska.
3. Finally, we looked into factors affecting the high gas prices and found out the price is majorly driven by the price of crude oil and weekly affected by state tax on gasoline. So, having relaxed taxes on gas by states will help curb with higher gas prices.

## Acknowledgement
* [AAA Website]{https://gasprices.aaa.com/state-gas-price-averages/}
* [GasBuddy Website]{https://www.gasbuddy.com/gaspricemap?lat=38.822395&lng=-96.591588&z=4}
* [EIA Website]{https://www.eia.gov/}
* [Tax Foundation Website]{https://taxfoundation.org/state-gas-tax-rates-2021/}
