# berchdel-test

# Overview

This test was founded in 1985 when a cartoonist Alison Bechdel asked in her comic strip, Dykes to Watch Out For, almost jokingly if movies have at least two women that talk to each other, not about a man. This is the premise of the Bechdel Test, to test the utmost minimum effort to include women in movies. Movies will pass the Bechdel Test if these three criteria are met:
- at least two women characters who have names (score of 1) 
- that talks to each other (score of 2)
- other than a man (score of 3)

# Dataset description 

- Bechdel test API : 9,330 movies & 5 variables 
- IMBD public csvs: title crew, title principals, title ratings, title basics, title ratings, title akas : 1,000,000 movies 

# Problem Statement & Data Questions : What combination of movie attributes makes a movie more or less likely to pass the Bechdel Test?

- Time - Have the Bechdel scores of movies improved over the years?
- Rating - Do movies with higher IMDB ratings have higher Bechdel scores?
- Director Gender - Do movies with female directors have higher Bechdel scores?
- Gender - What genders are more or less likely to pass the Bechdel Score?

# Type of analysis: Predictive (training a ml model to predict if movies depending on their parameters are likely to pass the Bechdel Test) & data visualization (answering all data questions)

# Project Roadmap

Cleaning, EDA & Plotting: 
1. Libraries
2. Load Data
- IMDb Data (8 CSVs)
- Bechdel Test API Call
3. Merge Data 
- Merge Name Related Tables 
- Merge Title Related Tables
- Apply Gender Detector
- Missing Values 
Modelling: logistic regression to predict passing the test, KNN,  feature selection, random forest, etc 
Analyse: answer all questions (data visualization), select best model & limitations 

# Limitations 

# Future projections

Answer following questions:
- Budget - Does the budget of a movie have any impact on its Bechdel score?
- Revenue - Do movies with higher Bechdel scores generate a larger revenue?
