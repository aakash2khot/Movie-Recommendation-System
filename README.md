# Movie-Recommendation-System

## Objective
The objective of this project is to build a movie recommendation system using the MovieLens 1M dataset. The system aims to suggest new movies to users based on their existing reviews.

## Dataset
The MovieLens 1M dataset contains 1 million ratings from users on various movies. The dataset also includes metadata such as movie genres.

## Implementation
### Preprocessing
Before implementing the recommendation system, the dataset underwent preprocessing. This involved handling missing values, removing unnecessary columns (while ensuring at least one movie of each genre is retained), and potentially normalizing the data.

### Algorithms Implemented
Neighborhood-based Collaborative Filtering: This method involves recommending movies based on the preferences of similar users. By calculating similarities between users or items, the system can suggest movies that similar users have liked in the past.

Combination of K-Means Clustering and Reduced Singular Value Decomposition (SVD): This approach involves two steps:

K-Means Clustering: Grouping similar users or movies into clusters using K-Means clustering. This helps in identifying patterns and similarities among users or movies.

Reduced SVD: Applying Singular Value Decomposition to reduce the dimensionality of the dataset. This helps in capturing the underlying latent factors that contribute to user preferences and movie characteristics.

### Testing of Recommendations
For testing the recommendation system:

Users provide ratings for some of their favorite movies from the dataset.
The system then recommends the top 5 new movies based on the provided ratings.
Explainability is provided for the recommendations, including why certain movies were suggested and when other movies would be recommended.

## Files Included
Exploratory Data Analysis (EDA) Notebook: This notebook explores the dataset, including data distribution, statistics, and visualizations.

Collaborative Filtering Notebook: This notebook implements the neighborhood-based collaborative filtering algorithm.

K-Means Clustering & SVD Notebook: This notebook implements the combination of K-Means clustering and Reduced SVD for recommendation.

## Conclusion
The movie recommendation system provides personalized suggestions to users based on their past preferences. By leveraging collaborative filtering and clustering techniques, the system can accurately recommend movies that users are likely to enjoy. Additionally, explainability is provided to enhance user trust and understanding of the recommendations.
