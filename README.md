# Movie Recommendation System

For this project, we built a movie recommendation system using the CiaoDVD dataset. The goal was to compare different ways of predicting ratings and see which one works better.

Dataset:
The dataset includes user ID, movie ID, movie category ID, rating, review ID, and review date.

Models used:
- Global average model
- Item-based collaborative filtering

Train/Test split:
The data was split into 80% training and 20% testing.

Evaluation:
We used RMSE and MAE to measure how accurate the predictions were.

Results:
Global Average:
RMSE = 1.08
MAE = 0.83

Item-Based CF:
RMSE = 1.00
MAE = 0.74

The item-based model performed better since it had lower error values.

How to run:
Open the notebook and run all the cells.

Dependencies : Python, pandas, numpy, matplotlib, scikit-learn

Group Members:
- Dennis Wahab and Rehan Cherian
