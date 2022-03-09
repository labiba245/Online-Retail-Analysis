# Online Retail Analysis

## Project Objective

Analyse and compare the sales of the online store based on region, datetime, type of customers (repeat or not) and items. 

## Code and Resources Used

Python version: 3.8

Packages used: pandas, matplotlib, seaborn

Data source: https://www.kaggle.com/carrie1/ecommerce-data


## Findings from explanatory analysis

1. Majority of the customers are from UK, where the online store is based in.
2. Most of the orders are made during the last quarter, particularly in October and November.
3. No orders are made on Saturdays and most orders are placed around 12pm.
4. Every month, 2 to 4 items are given for free, except in November 2011, when 14 items were given for free. 
5. Percentage of the revenue from repeat customers to the total monthly revenue on a monthly basis is:
    Month      |  Percentage
    -----------|---------------
    2010-12-31 |   62.71
    2011-01-31 |  39.01
    2011-02-28 |   42.77
    2011-03-31 |  44.90
    2011-04-30  |  41.66
    2011-05-31  |  55.73
    2011-06-30  |  56.91
    2011-07-31  |  52.90
    2011-08-31   | 49.14
    2011-09-30   | 52.54
    2011-10-31   | 55.23
    2011-11-30   | 61.44
    2011-12-31   | 28.34


## Some visualisations made on Tableau:
1. Heatplot of orders from each country: https://public.tableau.com/app/profile/labiba.islam/viz/OnlineRetail-SalesFromEachCountry/SalesFromEachCountry
2. Heatplot of orders from each country except the UK: https://public.tableau.com/app/profile/labiba.islam/viz/OnlineRetail-SalesFromEachCountryExceptUK/SalesFromEachCountryExceptUK
3. Top N (choose between 1 to 20) most sold items quantity ordered trend: https://public.tableau.com/app/profile/labiba.islam/viz/OnlineRetail-TopNItemsSalesTrend/TopNSoldItemsSalesTrend
4. Revenue generated during each quarter: https://public.tableau.com/app/profile/labiba.islam/viz/OnlineRetail-RevenueGeneratedDuringEachQuarter/RevenueGeneratedDuringEachQuarter

