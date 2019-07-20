
Alejandro Osborne
DATA 612 
July 9, 2019



# Project Planning Document

## Beer Recommendation System

The aim of this final project is to build a recommender system and produce quality recommendations by extracting insights from a large dataset, one consisting of at least one million ratings or at least ten thousand users and ten thousand items.

The dataset used is the Beer Reviews retrieved from https://data.world/socialmediadata/beeradvocate.  This dataset is a compilation of user information, beer information and beer ratings mined over a 10 year period. It contains 28,245 users, 39,884 kinds of beer and 1,000,000 ratings (I had to truncate the data use KNIME so that it would load into R comfortably, the initial dataset had closer to 1.6 Million ratings). It includes information such as User Id, brewery name, brewery id, and reviews based on aroma, color and taste on a scale of 1 to 5. However for the purposes of this project we will not be using all 13 varialbles and will likely narrow this down to 3 or 4.

To create the recommender system, both user based collaborative-filtering and item based algorithms will be used and compared, including User-to-User Collaborative Filtering, Item-to-Item Collaborative Filtering. While performing an exploratory analysis on the ratings, a look into the dataset's basic statistics will also be conducted to ascertain whether there is enough content to create recommendations taking into account ratings and amount of Reviews.

The implementation and evaluation will be hopefully be performed in R and Apache Spark.
