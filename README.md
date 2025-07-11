# 🎬 Netflix Movie Recommendation System using SVD

This project demonstrates how to build a personalized movie recommendation system using **Singular Value Decomposition (SVD)**, a popular collaborative filtering technique in machine learning.

## 💡 What is SVD?

SVD (Singular Value Decomposition) is a matrix factorization method that:
1. Starts with a matrix of user ratings for movies (most entries are missing).
2. Identifies hidden patterns and relationships between users and movies.
3. Predicts how users might rate unseen movies based on these patterns.

## 📊 Dataset Overview

- Contains over **24 million** user-movie ratings.
- Columns: `Cust_Id`, `Movie_Id`, `Rating`, `Year`, `Name`
- Rating scale: 1 to 5 stars

## 🧪 Key Steps in the Project

1. **Exploratory Data Analysis**
   - Count how many times each rating (1–5 stars) was given.
   - Find how many ratings each movie received.

2. **Movie Benchmarking**
   - Used a 60th percentile threshold to filter out less-rated movies for better accuracy.

3. **Model Building with Surprise Library**
   - Used `SVD` from `surprise` to build the recommendation model.
   - Employed `cross_validate()` for performance evaluation.

4. **Prediction**
   - Predicted ratings for unseen movie-user pairs.
   - Generated top movie recommendations for each user.

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `surprise` (SVD model, Dataset, Reader, cross_validate)

## 📈 Results

- Accurate prediction of user preferences based on prior ratings.
- Successfully built a recommendation system that can suggest relevant movies to users.

## 🧠 Why SVD?

SVD is powerful for:
- Handling sparse data (users haven’t rated all movies).
- Discovering latent features in user behavior.
- Providing personalized and scalable recommendations.

## 📌 Conclusion

This project offers a hands-on look at how platforms like **Netflix** recommend content. By applying SVD, we can understand user behavior and deliver meaningful suggestions at scale.

---

Feel free to check out the code and try generating your own recommendations!

#RecommendationSystem #SVD #Netflix #MachineLearning #CollaborativeFiltering #Python #SurpriseLibrary #MovieRecommender

