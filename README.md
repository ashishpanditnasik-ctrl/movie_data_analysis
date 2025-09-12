# Indian Movies Data Analysis

## Motivation
This project aims to analyze trends, patterns, and insights from a comprehensive dataset of Indian movies. By exploring features such as genre popularity, actor versatility, movie duration, and rating-votes relationships, the analysis provides a deeper understanding of the evolution and diversity of Indian cinema.

## Libraries Used
- **pandas**: Data manipulation and analysis
- **numpy**: Numerical operations
- **seaborn**: Statistical data visualization
- **matplotlib**: Plotting and visualization
- **plotly**: Interactive visualizations
- **scipy**: Scientific computations (Gaussian smoothing)

## Repository Files

- **friday_movie.ipynb**: Jupyter notebook containing all code for data loading, cleaning, transformation, visualization, and analysis.
  - Imports required libraries
  - Loads and inspects the movie dataset
  - Cleans and transforms data (numeric conversion, genre columns, log transformation)
  - Visualizes feature distributions (duration, rating, votes)
  - Analyzes genre popularity and rating-votes relationship
  - Examines actor versatility and exports results
  - Explores trends in movie duration and genre patterns over time

Other files:
These are output files generated thru the code that tabulate different results:
less_versatile.xlsx: An excel to capture versatality.
genre_distribution.html: To view genre distrubution.
nn_zero_count.xlsx: An excel to capture versatality.
sd_versatile.xlsx: An excel to capture versatality.

## Summary of Results

- **Genre Popularity**: Identified the most popular genres in Indian cinema and their trends over time.
- **Actor Versatility**: Quantified actor versatility based on genre diversity and highlighted both versatile and less versatile actors.
- **Duration Trends**: Explored how movie durations have changed across decades, including trends for highly-rated movies.
- **Rating-Votes Relationship**: Visualized the correlation between movie ratings and audience votes.
- **Genre Patterns**: Tracked the rise and fall of top genres and overall genre diversity across years.

## Acknowledgements

- IMDb for providing the movie dataset.
- Open-source Python libraries for enabling efficient data analysis and visualization.
- Community contributors for inspiration and support.
- Kaggle for Dataset

## How to use:
1. Set the data_path variable to the path of folder.
2. Run all the cells.

