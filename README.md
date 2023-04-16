### Success of Different Movie Types Analysis

**Author**: Aisha Hamid

### Overview

This project aims to analyze a movie dataset to identify the types of movies that are performing well in terms of production budget,worldwide gross,genre, runtime and rating_y to identify trends, patterns and relationships. We will use exploratory data analysis to generate insights for a business stakeholder.

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.
The key business questions are;
 1. What is the most profitable movie genre?
 2. What is the ideal production budget to produce a succesful movie?
 3. Which type of movie has the highest ratings?
 4. Does the movie runtime influence the success of a movie?	


### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

The different files have different formats,some are compressed CSV (comma-separated values) or TSV (tab-separated values) files and contains information on over 10,000 movies. The data is organized into several tables and several columns containing different information about the movies e.g the movie title, production budget, genre, runtime, and rating_y; each movie having a unique ID. Some of the challenges encountered during data preparation included missing values,outliers and placeholders.

### Methods

This project uses exploratory data analysis to generate insights for a business stakeholder.

## Results

The higher the production budget the higher the domestic and worldwide gross of a movie.There is a positive correlation between domestic_gross and worldwide_gross (0.944), meaning that as the domestic gross of a movie increases, the worldwide gross also tends to increase.
![image](https://user-images.githubusercontent.com/59911248/232331525-334b5b42-fed4-4da5-a96d-88c21926dc89.png)


The movie genre that is most profitable is Drama and also has the highest ratings.
![image](https://user-images.githubusercontent.com/59911248/232331933-c7fab266-304b-4e6e-8024-88cde4c17b6f.png)

Movie genre Drama has the highest average ratings which is also the most profitable genre.
![image](https://user-images.githubusercontent.com/59911248/232332096-9d985b8f-3525-4257-a448-21cd9f59cbf4.png)

## Conclusions
This analysis led to four conclusions;

The higher the production budget the higher the domestic and worldwide gross of a movie
The higher the domestic gross the higher the worldwide gross of a movie
The movie genre that is most profitable is Drama and also has the highest ratings.
The movie runtime doesnot influence the success of a movie as it has a weak negative correlation between both worldwide gross and production budget of -0.0078.

## Next steps
Further analysis could yield additional insights to improve predictions of successful movies

Stay up-to-date with industry trends and changes, and adjust strategies as needed to remain competitive. The movie industry is constantly evolving, and it is important to stay informed and adapt to new developments and challenges as they arise.
Conduct further research and analysis to better understand the specific factors that influence the success of movies in a target market e.g looking at industry data, conducting surveys or focus groups with target audiences, or analyzing critical reviews and social media sentiment.

## For More Information
See the full analysis in the [Jupyter Notebook](https://github.com/aisha2as/dsc-phase-1-project-v2-4/blob/master/student.ipynb).

