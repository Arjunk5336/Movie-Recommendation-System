# Movie Recommendation System
This is a simple Movie Recommendation System built using Streamlit, which allows users to receive personalized movie suggestions based on either Collaborative Filtering or Content-Based Filtering techniques.

Features:

Collaborative Filtering: Recommends movies based on the preferences of users with similar tastes.

Content-Based Filtering: Suggests movies that are similar in genre to a selected movie.

Interactive UI built with Streamlit.

Uses the MovieLens 100k dataset for recommendations.

User IDs for collaborative filtering range from 1 to 943.

Movie names are matched using fuzzy logic to handle typos or partial inputs.

Dataset Structure:

Ensure the following data files are available in the data/ folder:

u.data — User ratings (tab-separated).

u.item — Movie metadata (pipe-separated).

How It Works:

Collaborative Filtering:

Builds a user-movie rating matrix.

Computes cosine similarity between users.

Recommends movies liked by similar users.

Content-Based Filtering:

Builds a genre matrix from movie metadata.

Uses cosine similarity to find genre-wise similar movies.
