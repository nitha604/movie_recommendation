# movie_recommendation
🎬 Movie Recommendation System using Deep Learning Embeddings
📌 Project Description

This project implements a Movie Recommendation System using Deep Learning Embeddings in DLT2.ipynb. The system predicts user ratings for movies by learning hidden relationships between users and movies through embedding layers.

🎯 Objective
Build a recommendation model using Neural Collaborative Filtering
Learn user and movie embeddings
Predict ratings and recommend movies effectively
📂 Notebook Used

👉 DLT2.ipynb (Final Version)

⚙️ Workflow in Notebook
🔹 1. Import Libraries
NumPy
Pandas
TensorFlow / Keras
Scikit-learn
🔹 2. Data Loading
Dataset loaded (MovieLens or similar)
Contains:
User IDs
Movie IDs
Ratings
🔹 3. Data Preprocessing
Encoding of user IDs and movie IDs
Splitting dataset into:
Training set
Testing set
🔹 4. Model Building

The model uses embedding layers to represent users and movies in a dense vector space.

Architecture:
User Embedding Layer
Movie Embedding Layer
Flatten layers
Concatenation
Dense layers
Output layer (rating prediction)
🏗️ Model Flow
User ID ──► Embedding ─┐
                       ├──► Concatenate ─► Dense Layers ─► Predicted Rating
Movie ID ─► Embedding ─┘
🔹 5. Model Compilation
Loss Function: Mean Squared Error (MSE)
Optimizer: Adam
🔹 6. Model Training
Model trained on training dataset
Validation performed during training
🔹 7. Evaluation
Performance measured using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
