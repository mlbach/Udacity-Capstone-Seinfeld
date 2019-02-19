## Context
This repository holds my capstone project for Udacity's [Machine Learning Engineer Nanodegree program](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t).
I chose to work on a text classification problem, where I trained and tested different classifiers on dialogue scripts from the TV show Seinfeld. 
The goal was to predict the character given a line.

## Contents of the repository
- Code (Jupyter notebook)
- Project proposal (pdf)
- Project report (pdf)

## Data
Complete episode scripts are provided by [Seinology](http://www.seinology.com/). 
To scrape the data I used the code from this great repository: https://github.com/amanthedorkknight/the-seinfeld-chronicles

## Requirements
The whole project was implemented in a Jupyter notebook, using Python 3.5.5. 
The following additional libraries were used:
- numpy
- pandas
- matplotlib
- sklearn
- nltk
- keras
- Tensorflow
- tabulate

## Steps of the project
1. Loading of dataset
2. Cleaning and preprocessing of data
3. Data exploration
4. Training of classifiers with scikit-learn
5. Construction/training of ANNs
6. Generation of confusion map of the best-performing classifier
