AI-Powered Local Tourism Recommender  

This project is a Machine Learning-based Travel Recommender System that helps users find the best hotels based on their preferences and past interactions. The system uses a hybrid recommendation approach, combining content-based filtering and collaborative filtering to generate personalized hotel recommendations.

Features 
- Content-Based Filtering: Uses hotel features (e.g., amenities, location, rating) to recommend similar hotels.  
- Collaborative Filtering: Uses Singular Value Decomposition (SVD) on user-hotel interactions to recommend hotels based on user preferences.  
- Hybrid Recommendation System: Combines content-based and collaborative filtering for more accurate recommendations.  
- Preprocessing & Data Cleaning: Encodes categorical variables, handles missing values, and normalizes data.  

Dataset  
The dataset used in this project is based on hotel listings, including features like hotel name, city, rating, amenities, and price. The user-hotel interaction data is simulated for collaborative filtering.  

How It Works 
1. Load and preprocess data (handle missing values, encode categorical features, normalize ratings).  
2. Extract textual features from hotel descriptions using TF-IDF and compute hotel similarities using cosine similarity.  
3. Perform matrix factorization (SVD) on a user-hotel rating matrix to predict user preferences.  
4. Generate recommendations using content-based, collaborative, or hybrid filtering methods.  

Usage  
The system provides hotel recommendations based on:  
- A given hotel name (content-based filtering).  
- A specific user ID (collaborative filtering).  
- A combination of both (hybrid approach).  
