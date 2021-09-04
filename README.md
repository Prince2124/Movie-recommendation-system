# Movie-recommendation-system
Recommendation Systems and learn how to build a Movie Recommendation System using collaborative filtering by implementing the K-Nearest Neighbors algorithm.
# Data Set
I am using the MovieLens dataset from https://grouplens.org/datasets/movielens/latest/. The data consists of 105339 ratings applied over 10329 movies.
There are two data file:
1. The details.data dataset contains four columns:
'user_id', 'item_id', 'rating', 'timestamp'.
2. The Movie_Id_Titles dataset contains two columns:
'item_id' and 'title'.
# Approaches Tried
A. Deleting Unnecessary Columns

B. Data Cleaning

C. We meerge them together on item_id

D. Remove the NaN values from the dataset .Combining the files and making a pivot table

E. We used Cosine Similarity for finding the similarity between 2 movies.

F. We used K-Nearest Neighbors (e.g. K=6) find 6 most similar movies. These 6 movies will help in predicting for our desired movie. 


![image](https://user-images.githubusercontent.com/59818604/132088502-b56a39a3-2f42-4db1-a784-dfc0c73d025f.png)

