# KNN on Avocado Prices in 2020

This is a simple demonstration of the ability to classify data using the K-Nearest Neighbors (KNN) machine learning algorithm. Additionally, I want to understand how to tune the parameter K to maximize KNN accuracy on unseen data.

## About the Data

The ML applications in this notebook will be performed on the US avocado sales between 2015 and 2020, broken down by week. This is a public dataset from [kaggle](https://www.kaggle.com/timmate/avocado-prices-2020) that I will subset to yield a table with the following columns:

###### Numerical Features:
- `average_price`: the average price of a single avocado for that week
- `total_volume`: total amount of avocados sold (lbs)

###### Ordinal Features:
- `date`: entry collection date (weekly)
- `year`: entry collection year

###### Nominal Features:
- `type`: the type of avocados sold
- `geography`: the city or region of the observation
