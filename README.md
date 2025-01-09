# Personalized Movie Recommendation System 🎥

This project implements a **personalized movie recommendation system** using **collaborative filtering** in C++. The system predicts the ratings a user would assign to movies based on their past preferences and similarities to other users, and outputs a ranked list of recommended movies.

## 📋 Features

- **User-Movie Ratings Matrix**: Supports a CSV-based matrix as input.
- **Similarity Calculation**: Computes user-user similarities using collaborative filtering techniques.
- **Rating Prediction**: Predicts ratings for unrated movies.
- **Top N Recommendations**: Recommends the top N movies for a given user based on predicted ratings.
- **Performance Metrics**: Includes evaluation metrics like RMSE to measure accuracy.

---

## 📂 Dataset

The input dataset is a **user-movie ratings matrix** in CSV format, where:
- **Rows** represent users.
- **Columns** represent movies.
- Entries contain ratings (e.g., 1 to 5) or `0` for unrated movies.

### Example Dataset
```csv
UserID,Movie1,Movie2,Movie3,Movie4,Movie5
1,5,3,0,1,4
2,4,0,0,1,2
3,0,1,2,4,0
4,3,0,4,0,3
