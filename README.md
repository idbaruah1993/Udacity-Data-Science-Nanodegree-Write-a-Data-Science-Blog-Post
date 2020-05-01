# Udacity-Data-Science-Nanodegree-Write-a-Data-Science-Blog-Post

# 1. The Libraries
I used the following libraries
1. pandas
2. numpy
3. matplotlib
4. sklearn.model_selection (train_test_split module)
5. sklearn.metrics (r2_score, mean_squared_error)
6. sklearn.linear_model (LinearRegression module)
7. itertools (chain module)
8. seaborn

# 2. Motivation for project
I wanted to understand Seattle's AirBnB data to determine the critical determinants of AirBnB's price. The following 3 questions helped me understand that:

- What is the role of customer reviews in AirBnB? 
- Determine the costliest and cheapest areas
- What are the key determinants of the ratings?

# 3. File Details
The analysis is based on the following files:

1. Airbnb_Analyis_v1.ipynb: This is the iPython notebook with the results, graphs and calculations
2. listings.csv: A csv file with data for listings
3. calendar_data.csv:A csv file with data on dates available for listings and prices
4. reviews.csv: A csv file with data on reviews for listings


# 4. Results
The following results were found after the analysis:

1. We saw that the the higher rated AirBnBs on average have more comments compared to lower rated AirBnBs. We found the r-squared values in the Linear regression model (Ordinary least square model) of 0.3 and 0.4 for test and train datasets respectively on rating.
2. We found that the cheapest neighborhood is Rainier Beach while the most expensive  is Southeast Magnolia.
4. Transit and amenities (internet and dogs)see to be the key determinants of ratings.
 
# 5. Acknowledgements
The datasets are available on Kaggle and made available by AirBnB (https://www.kaggle.com/airbnb/seattle/data). Speical thanks to the Udacity team as well.
