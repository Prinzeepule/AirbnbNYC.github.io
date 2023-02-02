# AirbnbNYC.github.io
Market Analysis of NYC Airbnb

Airbnb New York City published data with reviews from January 1st, 2019 to July 9th, 2019 featuring above 25,000 listings that contains information about the hosts, prices, room types, and reviews of homestays in the 5 cities of New York called Borough.  
The dataset can be found here: https://www.kaggle.com/datasets/ebrahimelgazar/new-york-city-airbnb-market


TOOL USED - Microsoft PowerBi

Data Preparation: 


In PowerBi Transforms the datasets was checked for duplicates and nulls.
In the price dataset the price column was split to interger part and the “dollar” text part. The dollar text column was deleted and $ added to the new-price column while deleting the old column (column with int and text together).
Also in the “nbhood_full” column, the cities (Borough) was extracted to a standalone column named neighbourhood.
After ensuring the data is clean, the analysis of the data is done.


Analysis ideas: 


What is the average price, per night, of an Airbnb listing in NYC?
How does the average price of an Airbnb listing, per month, compare to the private   rental market?
How many adverts are for private rooms?
How do Airbnb listing prices compare across the five NYC boroughs?
Check the uploaded file for the datasets and analysis on the dashboard.
