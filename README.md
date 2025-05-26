# Recommendation_System_Filtering_based

COMPANY - CODTECH IT SOLUTIONS

NAME - G.NITHISH KUMAR REDDY

INTERN ID - CT04DN40

DOMAIN - MACHINE LEARNING

DURATION - 4 WEEKS

MENTOR - NEELA SANTHOSH

# Project Overview 

# 📚 Collaborative Filtering Recommendation System using Matrix Factorization (SVD)
This project demonstrates a Collaborative Filtering-based Recommendation System that utilizes Matrix Factorization, specifically Singular Value Decomposition (SVD), to provide personalized recommendations. The system is built using the scikit-surprise library and is evaluated using performance metrics like RMSE and MAE.

🔹 Objective
The primary goal is to predict a user’s potential rating for items (like movies) they haven’t interacted with, and to provide Top-N recommendations based on predicted preferences. This is achieved by analyzing user-item interaction data and uncovering latent factors that influence user preferences and item characteristics.

🔹 Methodology
The system employs Collaborative Filtering, a widely-used approach for recommendation systems. Specifically, Matrix Factorization techniques like SVD decompose the user-item interaction matrix into lower-dimensional representations. This factorization helps in:

Identifying latent features that represent user and item attributes.

Approximating the original interaction matrix, even for unseen user-item pairs.

🔹 Dataset
The project uses the MovieLens 100k dataset, which contains approximately 100,000 movie ratings from users. This dataset is a standard benchmark in recommendation system research.

🔹 Model Training & Prediction
The dataset is loaded and split into training and testing sets.

The SVD algorithm is trained on the known user-item interactions.

The trained model predicts ratings for the test set, generating estimated ratings for each user-item pair.

The predictions are evaluated using:

RMSE (Root Mean Squared Error): Measures the square root of the average squared differences between actual and predicted ratings.

MAE (Mean Absolute Error): Measures the average magnitude of prediction errors.

🔹 Top-N Recommendations
The system extracts the Top-N (e.g., Top-5) recommendations for each user by selecting items with the highest predicted ratings. This enables personalized content recommendations tailored to each user’s preferences.

🔹 Outcome
The resulting system provides:

Accurate rating predictions for user-item pairs.

Top-N recommendations for each user.

Performance evaluation using standard metrics (RMSE and MAE).

🔹 Technical Highlights
scikit-surprise: Python library used for building and evaluating recommendation systems.

SVD: Matrix factorization algorithm that efficiently uncovers latent patterns in sparse datasets.

MovieLens dataset: Provides a realistic benchmark for testing recommendation algorithms.

![image](https://github.com/user-attachments/assets/bea41e96-32a5-4c0b-b256-557079011bcd)
