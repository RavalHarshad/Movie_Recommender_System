# Movie_Recommender_System

🎬 Movie Recommender System

A Machine Learning based Movie Recommender System that suggests movies to users based on similarity and user preferences.

📌 Project Overview

This project builds a recommendation system using Content-Based Filtering to recommend movies similar to a selected movie.

The dataset is taken from Kaggle and includes movie metadata such as:

Title

Genre

Keywords

Cast

Crew

Overview

The system analyzes movie features and recommends top 5 similar movies.

🚀 Features

Content-Based Movie Recommendation

Cosine Similarity Algorithm

Data Preprocessing & Feature Engineering

Clean and Simple Python Implementation

Optional Streamlit Web App

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Streamlit (Optional UI)

⚙️ How It Works

Merge movies and credits dataset

Select important features (genres, keywords, cast, crew, overview)

Combine features into one text column

Convert text into vectors using CountVectorizer

Calculate Cosine Similarity

Recommend top similar movies
