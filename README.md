Movie Recommender System

Overview

This repository contains the implementation of a simple movie recommendation system that suggests similar movies based on user ratings. While not a fully robust recommender engine, it provides a straightforward method for movie recommendation.

Features

- Load and preprocess user movie ratings and movie titles data.
- Perform exploratory data analysis (EDA) on movie ratings.
- Implement a similarity-based recommendation system using correlation metrics.

Dataset

The project utilizes two datasets:

u.data: Contains user movie ratings with columns including user_id, item_id, rating, and timestamp.

Movie_Id_Titles: Contains a mapping of item_id to movie titles.

Both datasets are preprocessed and merged to facilitate the recommendation process.


Requirements

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

How It Works

The system:

- Merges user rating data with movie titles based on item IDs.
- Performs EDA to understand the distribution of movie ratings and number of ratings per movie.
- Calculates pairwise movie similarity scores based on user ratings.
- Recommends movies that are most similar to a user-selected movie.

Visualization

Includes histograms and jointplots of movie ratings, providing insights into the general distribution and user preferences.
