Scenario 1: User-Based Collaborative Filtering

Dataset Link:
https://www.kaggle.com/datasets/grouplens/movielens-100k

Description:
In this scenario, user-based collaborative filtering is used to recommend movies based on similarities between users. A user-item interaction matrix is created using ratings data, and cosine similarity is applied to identify users with similar preferences. The system predicts ratings for unseen movies by considering ratings from similar users. Based on these predictions, top-N movie recommendations are generated. The model performance is evaluated using metrics like RMSE and MAE.

Scenario 2: Item-Based Collaborative Filtering

Dataset Link:
https://www.kaggle.com/datasets/grouplens/movielens-100k

Description:
In this scenario, item-based collaborative filtering is implemented to recommend movies similar to those a user has already liked. An item-user matrix is constructed, and similarity between items is computed using cosine similarity or Pearson correlation. The system recommends items that are most similar to a user's previously rated items. This approach is more scalable and efficient for large datasets. The recommendations are evaluated using RMSE and Precision@K to measure accuracy and relevance.