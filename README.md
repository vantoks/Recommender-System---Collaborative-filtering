# Recommender_System_Collaborative_filtering
Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user. These systems have become ubiquitous can be commonly seen in online stores, movies databases and job finders. In this notebook, I will explore recommendation systems based on Collaborative Filtering and implement simple version of one using Python. Objective: Create recommendation system based on collaborative filtering.

Similarity computation:
I am going to be using Pearson correlation to stablish the similary between the active user and users from the dataset. Pearson correlation is invariant to scaling, which is an important feature for this type of system. For example, two users might rate two series of items totally different in terms of absolute rates, but they would be similar users with similar rates in various scales.
