# EECS 731 Project 3

This is Andre Kurait's third project for EECS 731, Data Science in Fall 2019.
For this project, I analyzed several clustering models to link similar movies.

## Project Requirements
### Weekend movie trip
#### Blockbuster or art film?
1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the one of the MovieLens datasets from https://grouplens.org/datasets/movielens/
3. Load the data set into panda data frames
4. Formulate one or two ideas on how the combination of ratings and tags by users helps the data set to establish additional value using exploratory data analysis
5. Build one or more clustering models to determine similar movies to recommend using the other ratings and tags of movies by other users as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

## Project structure
```bash
.
├── MovieLens.ipynb
├── README.md
└── data
    ├── README.txt
    ├── links.csv
    ├── movies.csv
    ├── ratings.csv
    └── tags.csv
```

## Conclusion
Overall, I was able to create a recommendation algorithm that gave recommendations that made sense to people who have viewed both movies.