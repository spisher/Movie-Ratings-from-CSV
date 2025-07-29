#  Movie Ratings from CSV

This project is a simple NumPy-based tool to analyze movie data from a CSV file.

##  Description

It performs basic data analysis on a CSV file that contains information about movies, such as:

- Movie title
- Release year
- Genre
- Rating

Using NumPy, the program calculates:

- Average rating of all movies
- Standard deviation of ratings
- Filters movies by genre

##  CSV Format

The CSV file should look like this:

```
Title,Year,Genre,Rating
Inception,2010,Sci-Fi,8.8
Titanic,1997,Romance,7.8
Avengers: Endgame,2019,Action,8.4
Interstellar,2014,Sci-Fi,8.6
...
```

##  Features

- Read and parse CSV file using `numpy.genfromtxt`
- Compute average and standard deviation of ratings
- Group movies by genre
- Filter and display movies by specific genre