# Microsoft-Movie-Analysis

**Author**: [George Kariuki](mailto:george.kariuki1@student.moringaschool.com)


## Overview

This project analyzes the needs of the new Microsoft Movies Director, whose aim is to enter into the movie and short film space dominated by other studios. A lot of descriptive analysis with visual backing has revealed that a successful studio is a healthy mix amongst a myriad of features such as budget, directors, the right genres and other fundamental features.

## Business Problem
Microsoft Studios are excited to delve into the world of creative arts videos and movie production. To aid the head of Microsoft Movies I ahve created this project that attempts to understand the movies at the box office with an aim to explore the kind of films that are doing well at the box office. Some of the questions we shall explore and investigate include:
### 1. Genres 
    - What are the best performing genres at the box office?
### 2. Directors - Best performing directors by revenue and volume
    - Who are the best performing directors at the box office?
### 3. Studios - Best performing studios by revenue and volume
    - Which studios are the best performing studios at the box office?

## Data
Data for this project found in 3 csv files and one sqlite3 database file. Using Python Pandas and SQLite3 modules, I was able to read, merge, process and analyse the data from the different datasets into one dataframe. The data provided information on movie titles, runtime, vote count, genres, revenue, budgets, directors and studios.

## Methods

This project uses historical data from the IMDB and other files to enable summarization of primary properties of a dataset. 

## Results

The best length of a movie is between 90 and 110 minutes

![movie_runtimes.png](./images/"Hist Movie Runtimes.png")

The best time to release movies were observed to be between October and November

![movie_release.png](./images/"Hist Movie Release Month.png")

There is a strong correlation between votes and revenues.

![vote_v_release.png](./images/"Vote v Revenue.png")

## Conclusions

This analysis leads to three recommendations to carve a niche for Microsoft Studios:

- **Maintain a 90 - 110 movie runtime.** While it may be tempting to have a 10 hour long movie, the population revealed that the favorable periods for a movie were in this range.
- **Release movies in October to December.** A lot of movies were released in this period. Use this opportunity to carve out a portion of the market to watching our movies.
- **Focus on high vote counts.** More effort put into making a great movie, was rewarded with a high vote count which has a strong correlation with the revenues earned. 


## For More Information

See the full analysis in the [Jupyter Notebook](./student.ipynb) or review this [presentation](./student.pdf).

## Repository Structure

```
├── zippedData
├── images
├── README.md
├── student.pdf
└── student.ipynb
```

