

# Netflix Movie Data Analysis Project

## Overview

This project performs an exploratory data analysis on a dataset of Netflix movies. The goal is to uncover insights into movie genres, popularity, and release trends.

## Project Description

This project aims to analyze a dataset containing information about movies available on Netflix. The analysis involves data cleaning, preprocessing, and visualization to answer several key questions about movie trends and characteristics on the platform.

## Questions Explored

The analysis addresses the following questions:

1.  What is the most frequent genre of movies released on Netflix?
2.  What genres have the highest votes?
3.  What movie got the highest popularity? What's its genre?
4.  What movie got the lowest popularity? What's its genre?
5.  Which year has the most filmed movies?

## Dataset

The dataset used for this analysis is named `mymoviedb.csv`. It contains the following columns:

  * `Release_Date`: The release date of the movie.
  * `Title`: The title of the movie.
  * `Overview`: A brief description of the movie.
  * `Popularity`: A popularity score for the movie.
  * `Vote_Count`: The number of votes the movie received.
  * `Vote_Average`: The average vote score for the movie.
  * `Original_Language`: The original language of the movie.
  * `Genre`: The genre(s) of the movie (comma-separated).
  * `Poster_Url`: The URL of the movie poster.

**Data Cleaning and Preprocessing Steps:**

  * The `Release_Date` column was converted to datetime format, and only the year was extracted.
  * Irrelevant columns (`Overview`, `Original_Language`, `Poster_Url`) were dropped.
  * The `Vote_Average` column was categorized into "not popular," "below average," "average," and "popular" based on quartiles.
  * The `Genre` column, which contained comma-separated values, was split into individual genres, and the DataFrame was "exploded" so that each row represents a single movie-genre combination.
  * Missing values were dropped from the dataset.
  * The `Genre` column was cast to a categorical data type.

## Analysis and Visualizations

The analysis is performed using Python and various data science libraries. Key visualizations include:

  * **Genre Distribution:** A count plot showing the distribution of movie genres.
  * **Votes Distribution:** A count plot illustrating the distribution of `Vote_Average` categories.
  * **Release Date Distribution:** A histogram displaying the number of movies released per year.

## Key Findings

Based on the analysis, the following key insights were drawn:

  * **Most Frequent Genre:** Drama is the most frequent genre in the dataset, accounting for over 14% of all movie genres.
  * **Genres with Highest Votes:** Approximately 25.5% of the dataset falls into the "popular" vote category. Among these, Drama movies received the highest popularity, making up over 18.5% of the popular movies.
  * **Highest Popularity Movie:** "Spider-Man: No Way Home" has the highest popularity rate in the dataset. Its genres are Action, Adventure, and Science Fiction.
  * **Lowest Popularity Movie:** "The United States vs. Billie Holiday" and "Threads" share the lowest popularity rate in the dataset. Their genres include Music, Drama, War, Sci-Fi, and History.
  * **Year with Most Filmed Movies:** The year 2020 has the highest filming rate in the dataset.

## Tools and Libraries

  * **Python:** Programming language
  * **pandas:** Data manipulation and analysis
  * **numpy:** Numerical operations
  * **matplotlib.pyplot:** Data visualization
  * **seaborn:** Enhanced data visualizations

## How to Run

1.  **Clone the repository (or download the notebook):**
    ```bash
    git clone <repository_url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Netflix Movie Data Analysis Project
    ```
3.  **Ensure you have the necessary libraries installed:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
4.  **Place the `mymoviedb.csv` file in the same directory as the notebook.**
5.  **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook "Netflix Movie Data Analysis Project.ipynb"
    ```
6.  **Run all cells** in the notebook to reproduce the analysis and visualizations.
