# Movie Recommendation System

A Content-Based Movie Recommendation System built using Python and Machine Learning that suggests similar movies based on a user's selected movie. The system analyzes movie metadata such as genres, keywords, cast, and overview to recommend movies with similar characteristics.

Recommendation systems are widely used by platforms like Netflix, Amazon Prime, and YouTube to provide personalized suggestions to users.

# 📌 Project Overview

The goal of this project is to build a movie recommendation engine that recommends movies similar to the one selected by the user.

The system uses content-based filtering, which recommends items based on similarity between item features such as genre, cast, and storyline.

This project demonstrates how machine learning techniques can be used to build intelligent systems that improve user experience by providing personalized suggestions.

# 🚀 Features

1. Movie recommendation based on similarity

2. Uses Content-Based Filtering

3. Data preprocessing and feature engineering

4. Vectorization using CountVectorizer

5. Similarity calculation using Cosine Similarity

6. Interactive interface using Streamlit

7. Displays movie posters using API

8. Fast recommendations for user input

# 🧠 Machine Learning Workflow

The project follows these steps:

1. Data Collection

2. Data Preprocessing

3. Feature Engineering

4. Text Vectorization

5. Similarity Calculation

6. Recommendation Function

7. Frontend Interface

# 📂 Dataset

The dataset contains information about movies including:

1. Movie title

2. Genres

3. Keywords

4. Cast

5. Crew

6. Overview

7. Movie ID

Common datasets used for such projects include TMDB or MovieLens datasets which contain movie metadata and ratings.

# 🛠️ Technologies Used
## Programming Language

1. Python

2. Libraries

3. Pandas

4. NumPy

5. Scikit-learn

6. NLTK

7. Pickle

## Machine Learning

Content Based Filtering

Cosine Similarity

Vectorization

# 📁 Project Structure
movie-recommendation-system
│
├── data
│   ├── movies.csv
│   └── credits.csv
│
├── notebooks
│   └── movie_recommendation.ipynb
│
├── model
│   ├── similarity.pkl
│   └── movie_list.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── screenshots

# ⚙️ Installation
## 1️⃣ Clone the repository
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system

## 2️⃣ Install dependencies
pip install -r requirements.txt

## 3️⃣ Run the application
streamlit run app.py

## 📊 How It Works
## 1. Data Processing
Combine relevant features like:

1. genres

2. keywords

3. cast

4. overview

## 2. Feature Engineering
All features are merged into a single text feature called tags.

## 3. Vectorization
The tags are converted into vectors using:
CountVectorizer

## 4. Similarity Calculation
Cosine similarity is used to measure similarity between movies.

## 5. Recommendation
When a user selects a movie:

1. The system finds its vector.

2. Computes similarity with all movies.

3. Returns the top 5 most similar movies.

# 🎥 Application Interface
Users can:

1. Select a movie from the dropdown

2. Click Recommend

3. Get top 5 similar movies


Each recommendation includes:

1. Movie poster

2. Movie title


# 📚 Learning Outcomes
Through this project, we learn:

1. Machine Learning fundamentals

2. Recommendation system algorithms

3. Data preprocessing techniques

4. Vectorization techniques

5. Similarity measures

# 🤝 Contribution
Contributions are welcome!

Steps:

1. Fork the repository

2. Create a new branch

3. Make changes

4. Submit a Pull Request


