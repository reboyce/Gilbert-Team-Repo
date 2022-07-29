# Gilbert Crew Capstone Project
#### Ryan Burger, Hannah Bowman, Telma Ashton, Reece Boyce, Chris Christensen 
![](https://c.tenor.com/0DnrqvZqHGUAAAAC/movie-excited.gif)

## Summary
In this project we were charged with exploring what types of films are currently doing the best at the box office using different samples of available data. Through our analysis we translated our findings into actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create.

After exploring the Imdb and Rotten Tomatoes database we were able to come to 3 recommendations based of data analysis on genre, runtime, actors, directors/writers, revenue and competitor studios.

## Data Science Steps 

### Obtaining
We obatined the dataframes from the client and moved them into our repository. 

### Cleaning
There was some inital data cleaning that needed to be done. There were multiple null values that needed to be changed to 0 or dropped completely from the dataframe so that the data could be analyzed correctly. 

### Exploring
Basic exploration was conducted to gain a better understanding of the data we were given. This helped in putting us into the right direction to formulize the reccomendations. 

### Modeling
After cleaning and exploring the data we were able to create tables and visualizations that led us to be able to interpret the data. 

### Interpeting
Here we came to a final conclusions of our three recommendations gathered in the rest of the data science steps 


## Sources

### DataFrames 
- [IMDB](https://github.com/reboyce/Gilbert-Team-Repo/blob/main/Notebooks/Files/im.db.zip)
- [Rotten Tomatoes Movie Information](https://github.com/reboyce/Gilbert-Team-Repo/blob/main/Notebooks/Files/rt.movie_info.tsv.gz)
- [Rotten Tomatoes Reviews](https://github.com/reboyce/Gilbert-Team-Repo/blob/main/Notebooks/Files/rt.reviews.tsv.gz)
- [TMDB Movies](https://github.com/reboyce/Gilbert-Team-Repo/blob/main/Notebooks/Files/tmdb.movies.csv.gz)


### Notebooks
All of our data files from individual exploration, version changes and final notebook can be found on the link below:
- [Notebooks link](https://github.com/reboyce/Gilbert-Team-Repo/tree/main/Notebooks)

### Presentation
Our presentation shows a summary of our data analysis using visualizations from Matplotlib and Seaborn libraries, our findings from the analysis and statistical tests, and our 3 final recommendations.

-[Presentation link]()


## Navigating Repository
Instructions on navigating repository:
- Click [here](https://github.com/reboyce/Gilbert-Team-Repo) to access our repositoy. The link will go to the main page of the repository
- Go to Notebooks folder and inside the folder you will find:
    - Files folder with all the data explored for our analysis
    - Image folder with the ER diagram for the Imdb data files
    - Ryan's Notebook
    - Reece's Notebook
    - Hannah's Notebook
    - Telma's Notebook
    - Chris's Notebook
    - Final Notebook

- Back to the main on repository link you will find each team member individual branch with a copy of the Notebooks file from main

   
## Libraries
Below we have all the libraries we used for our code (also referenced on the repository final notebook):

- import pandas as pd
- import numpy as np
- import matplotlib.pyplot as plt
- import seaborn as sns
- import scipy.stats as st
- from math import sqrt
- import warnings
  warnings.simplefilter(action='ignore', category=FutureWarning)

### Summary 

