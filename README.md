# Bayesan-Networks-on-Song-Popularity
## Song Popularity Prediction Using Bayesian Networks: A Probabilistic Approach
This repository contains the code and analysis for predicting song popularity using Bayesian Networks. The project explores three probabilistic models—Tree-Augmented Naive Bayes (TAN), Tree Search, and Tabu Search—to understand the relationships between song features (e.g., track_genre, danceability, loudness, tempo) and popularity. The goal is to provide actionable insights for artists and industry professionals to maximize song success.

## Key Features
Three Bayesian Network Models:

*    TAN (Tree-Augmented Naive Bayes): Extends Naive Bayes by allowing dependencies between features.

*    Tree Search: Learns the network structure using a tree-based algorithm.

*    Tabu Search: Uses a heuristic optimization algorithm to find the best network structure.
     Conditional Probability Distributions (CPDs): Calculated for each model using Maximum Likelihood Estimation.

## Inference Questions:

Which track_genre maximizes popularity?

How do loudness and tempo jointly affect popularity?

What is the optimal combination of features for high popularity?

Visualizations: Interactive plots to compare model results and interpret findings.
Acknowledgments
Inspired by Bayesian Network applications in predictive modeling: https://github.com/diegochine/videobayes

Dataset sourced from (https://www.kaggle.com/datasets/thedevastator/spotify-tracks-genre-dataset?select=train.csv).
