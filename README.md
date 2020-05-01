# Udacity-Data-Science-Nanodegree-Write-a-Data-Science-Blog-Post

# 1. Libraries
The libraries that I used were
1. pandas
2. numpy
3. matplotlib
4. sklearn.model_selection (train_test_split module)
5. sklearn.metrics (r2_score, mean_squared_error)
6. sklearn.linear_model (LinearRegression module)
7. itertools (chain module)
8. seaborn

# 2. Project Motivation
I chose to examine the AirBnB data from Seattle to better understand which factors contributed to the price of an AirBnB. I formulated 3 questions using the CRISP-DM process to elucidate the findings.

- Which neighborhood is the most expensive and which is the cheapest?
- How do customer reviews factor into the AirBnB? Are there more comments for highly or poorly rated AirBnBs?
- What factors determine rating? Can we predict rating using a model?

# 3. File Descriptions
These are the following files I used to complete this analysis:

1. DataScience_Project1.ipynb: The iPython notebook containing all calculations, figures, and findings pertaining to the project.
2. calendar.csv: A file containing all of the dates available for listings as well as price
3. listings.csv: A file containing all of the information for listings
4. reviews.csv: A file containing reviews for the listings
# 4. Summary
The following results are a brief summary of the data exploration contained in the project:

1. The most expensive neighborhood is Southeast Magnolia and the cheapest is Rainier Beach.
2. AirBnBs with higher ratings tend to have more comments than AirBnBs with low ratings.
3. The LinearRegression model found r-squared values of 0.4 and 0.29 for training and test data respectively on rating.
4. The variables that had the highest effect on rating were transit, and amenities (internet and dogs).
# 5. Acknowledgements
The data was hosted on Kaggle and made available by [AirBnB] (https://www.kaggle.com/airbnb/seattle/data) Thank you to the Udacity team for creating this project and associated lessons.
