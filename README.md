# Movie Recommendation System

## Overview

This is a simple movie recommendation system that suggests movies based on their textual descriptions, such as genre and overview. The system uses natural language processing (NLP) techniques and cosine similarity to find movies that are similar to a given movie. The goal of this project is to provide personalized movie recommendations to users based on their preferences.

## Features

- **Movie Data Processing:** Combines genre and overview into a single text field (`tags`) for each movie.
- **Text Vectorization:** Converts the text data into numerical vectors using the `CountVectorizer` from the `sklearn` library.
- **Similarity Calculation:** Uses cosine similarity to compute the similarity between movies.
- **Movie Recommendation:** Recommends the top 5 most similar movies to the user based on a given movie title.
- **Precision Evaluation:** Calculates the precision of the recommendations by comparing them to a list of known relevant movies.

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `sklearn`

You can install the required libraries using the following command:

```bash
pip install pandas numpy scikit-learn
