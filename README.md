# Movie-recommendation-system
Recommendation Systems and learn how to build a Movie Recommendation System using collaborative filtering by implementing the K-Nearest Neighbors algorithm.
## collaborative filtering
collaborative filtering method is usually based on collecting and analyzing information on user’s behaviors, their activities or preferences, and predicting what they will like based on the similarity with other users.

![image](https://user-images.githubusercontent.com/59818604/132089785-0c7fb709-fadf-4b3b-b157-563b0b565751.png)

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

# Recommendation Stategies
A. KNN (K- Nearest Neighbor)
B. Cosine Similarity
C. Popularity (most rated) based recommender

# Screenshot of output

![Stastical_plot](https://user-images.githubusercontent.com/59818604/132090325-3df419c6-fdab-4aaf-8f36-dadf1d7d7304.png)

![Movie_Recommendation](https://user-images.githubusercontent.com/59818604/132090306-418f85e8-bc21-4e58-83b7-6ec23f2bc6ea.png)



# References
https://www.analyticsvidhya.com/blog/2020/08/recommendation-system-k-nearest-neighbors/

