# DSA4212-Recommendation-Algorithms
DSA4212 Project: Movie Recommendation Algorithms Based on Collaborative and Content-based Filtering

We Implemented several collaborative and content-based filtering algorithms from scratch, using the MovieLens-1M dataset
* Collaborative filtering algorithms: User-CF, Item-CF, and SVD++ (SVD with Implicit Feedback)
* Content-based filtering algorithms: User profile correlation-based and Item profile correlation-based (TF-IDF)

Codes can be seen in `recommendation-algorithms.ipynb`.

## Dataset

We use MovieLens-1M dataset (link: https://grouplens.org/datasets/movielens/1m/) for this project. It describes people’s expressed preferences for movies. These preferences are formed in (user, item, rating, timestamp), of each sample the rating varies from 0 to 5 (0 means the user has not rated before).

## Experimental Results
### RMSE Result of Different Models
Model | RMSE
:--: | :--:
Matrix Factorization  | 0.92
SVD | 1.55
**SVD++** | **0.89**
User-Based CF | 1.96
Item-Based CF | 1.27
User Profile Similarity | 1.88
Movie Profile Similarity | 2.35
