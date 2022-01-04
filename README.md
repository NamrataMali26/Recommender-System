# Recommender-System
Movie recommender system using collaborative filtering techniques to recommend movies to users, similar to how Netflix makes movie recommendations. 

## Data set Used
used MovieLens 100K data to test different models.
Download MovieLens 100K data from:
https://www.kaggle.com/prajitdatta/movielens-100k-dataset.

Implemented User-User method and Item-Item method to calculate the ratings of each user to each item. In both methods, calculated the similarity between users (or items) using Pearson correlation. Set the number of neighbors to 10 & recommnended 10-best NEW movies to each user based on ratings. ( note: The user should not have watched the recommended movies) 

## Results
Generated two files pred_user_user.txt and pred_item_item.txt.


