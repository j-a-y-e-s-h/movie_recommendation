# Movie Recommendation System

This repository contains files for a movie recommendation system.

Download Data from Kaggle [Link](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## Usage

### Initial Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/j-a-y-e-s-h/movie_recommendation.git
   ```
2. Navigate to the repository directory:

   ```bash
   cd movie_recommendation
   ```
3. First, run the `movie-recommender.ipynb` file in your Jupyter Notebook environment. This notebook performs data preprocessing and model training.

### Running the Recommendation System

After running the `movie-recommender.ipynb` file, it generates two files:

- `movie_dict.pkl`: A pickle file containing movie data.
- `similarity.pkl`: A pickle file containing similarity scores.

Now, run the `app.py` file to start the recommendation server:

```
streamlit run app.py
```

The application will launch in your browser, allowing you to select your favorite movies and get recommendations.

## Files

- `movie-recommender.ipynb`: Jupyter Notebook containing data preprocessing and model training.
- `app.py`: Python script for running the movie recommendation server.
- `Untitled.jpg`: Image file used in the recommendation system interface.
- `tmdb_5000_credits.csv` data file.
- `tmdb_5000_movies.csv` data file.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- streamlit
- Pillow (PIL)

## Acknowledgments

- The data used in this project is from TMDb (The Movie Database).
