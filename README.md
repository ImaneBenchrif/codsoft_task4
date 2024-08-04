# codsoft_taskno5


# Content-Based Movie Recommendation System

## Description


This project demonstrates a simple content-based movie recommendation system using TF-IDF Vectorization and Cosine Similarity. The system recommends movies based on their genre similarity. The dataset used for this example is loaded from a local file (movies.txt), which contains movie titles and genres.

## Features

- Data Loading: Load movie data from a CSV file. 

- Feature Extraction: Convert movie genres into numerical features using TF-IDF Vectorizer.

- Similarity Calculation: Compute the cosine similarity matrix to measure similarity between movies.

- Recommendation Function: Recommend movies based on the cosine similarity of genres.

## Prerequisites

Ensure you have the following libraries installed:

- 'pandas'

- 'scikit-learn'

You can install these dependencies using pip:

        pip install pandas scikit-learn
        
## Data

The dataset used in this project should be in CSV format with the following columns:

- movieId: Unique identifier for each movie

- title: Name of the movie

- genres: Genres of the movie (pipe-separated)
