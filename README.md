# Movie Recommendation System

This project implements a movie recommendation system using Python, leveraging machine learning techniques for text analysis and similarity computation.

## Overview

The system allows users to:
- Search for movies by title, applying text preprocessing for accurate matching.
- Display movie recommendations based on similarity scores calculated using TF-IDF vectorization and cosine similarity.
- Utilize an interactive interface with IPython widgets for a user-friendly experience.

## Requirements

- Python 3
- pandas
- scikit-learn
- numpy
- ipywidgets

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Rishi-Priya01/Movie_Recommendation.git
   cd movie-recommendation-system
2. Install dependencies:
   pip install pandas scikit-learn numpy ipywidgets
## usage
Run the script:
Interact with the system:
1. Enter a movie title in the input box to see recommendations.
2. Results display movies similar to the entered title based on user ratings and genre.
   
## components
recommendation_system.ipynb
Imports: Libraries including pandas, scikit-learn, and ipywidgets.
Data Loading: Reads movies.csv containing movie titles and genres.
Text Processing: Cleans movie titles and applies TF-IDF vectorization.
Search Functionality: Enables searching for movies and displaying recommendations.
User Interface: Uses ipywidgets for an interactive input/output interface.
Example Output
Input: "Toy Story"
Recommendations: List of movies similar to "Toy Story" based on user ratings and genre.
License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
pandas: Data manipulation and analysis in Python.
scikit-learn: Machine learning library for Python.
ipywidgets: Interactive HTML widgets for Jupyter notebooks.
