# Recommendation-system
1 algorithm

# Movie Recommendation System

A machine learning project that recommends movies to users based on similarity between movie features.

---

## Problem Statement

Recommendation systems are widely used in platforms such as Netflix, Amazon, and YouTube.  
The goal of this project is to build a movie recommendation system that suggests similar movies based on user preferences.

---

## Dataset

This project uses the **MovieLens dataset**.

Dataset source:  
https://www.kaggle.com/datasets/grouplens/movielens-100k

The dataset contains:

- Movie titles
- User ratings
- Genre information

---

## Project Structure
movie-recommendation-system/ │ ├── data/ │   └── dataset link or instructions │ ├── notebooks/ │   └── recommendation_system.ipynb │ ├── src/ │   └── recommender.py │ ├── models/ │   └── trained_model.pkl │ ├── requirements.txt └── README.md

---

## Methodology

Steps followed in the project:

1. Data preprocessing
2. Feature extraction using TF-IDF
3. Similarity computation using cosine similarity
4. Generating top-N movie recommendations

---

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Results

The recommendation system successfully identifies movies with similar themes and genres.

Example:

Input movie:

Interstellar 


## Recommended movies:
1. The Martian <br />
2. Gravity <br />
3. Inception <br />
4. Arrival <br />
5. Contact


# How to Run the Project

## Clone the repository
git clone
https://github.com/yourusername/movie-recommendation-system.git

## Install dependencies
pip install -r requirements.txt

## Run the notebook
jupyter notebook notebooks/
recommendation_system.ipynb


# Future Improvements

Implement collaborative filtering

Add deep learning recommendation models

Deploy the system as a web application




# Author

Shridhar Shukla
