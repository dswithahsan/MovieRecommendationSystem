Content-Based Movie Recommendation System

Overview

This project implements a content-based recommendation system that suggests movies similar to a given input. By analyzing key attributes such as director, cast, title, and keywords, the system identifies and ranks similar movies. This approach is commonly used by streaming platforms like Netflix to enhance user experience.

Methodology

Feature Extraction: Movie attributes are processed to create meaningful representations.

TF-IDF Vectorization: Text data is transformed into numerical vectors to quantify relationships.

Cosine Similarity: A mathematical measure used to determine the closeness of movies based on extracted features.

Recommendation System: When a user inputs a movie title, the algorithm identifies and returns the most similar movies from the dataset.

Technologies Used

Python

Pandas (Data manipulation and processing)

NumPy (Numerical operations and optimizations)

Scikit-Learn (TF-IDF vectorization, cosine similarity computation)

Dataset

The recommendation system is trained on a dataset containing 5000 movies, with the following key attributes:

Movie Title

Cast

Crew

Keywords

Plot Summary

Installation & Usage

Prerequisites

Ensure you have Python installed along with the required libraries.

Setup Instructions

Clone the repository:

git clone https://github.com/dswithahsan/MovieRecommendationSystem/

Install dependencies:

pip install pandas numpy scikit-learn

Run the Jupyter Notebook or Python script to execute the recommendation system.

Example Usage

Given an input movie such as "Inception", the system will return a list of similar movies, such as:

Interstellar

The Prestige

Shutter Island

Repository Contents

Content Based Recommendation System.ipynb – Main notebook containing implementation details.

movies_dataset.csv – Dataset used for building recommendations.

Contribution

Contributions are welcome! Feel free to fork the repository, enhance the algorithm, and submit pull requests.

