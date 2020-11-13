# Recommendation-System
This is a recommendation system built as a part of an interview assignment

Objective: 
Build a Recommendation System, System should be based on the categorical data like category, tags of posts, and liked and viewed posts category for the user.
End result should be a system that:
  1. Recommend posts for the given user.
  2. Recommend similar posts for the given post.

Approach followed:

Tool used: Python
Libraries Used: Pandas, Numpy, Scipy, Sci-kit Learn, Seaborn, Matplotlib
Used Cosine similarity to measure how the interests are similar between two users, so that would help in better recommendation.
Used sparse matrix because there are lot of categories and the users are only interested in a few.
