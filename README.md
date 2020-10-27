# Understanding League of Legends: What makes a team win a game?

## About the project

For this individual university I inspected the characteristics and statistics of competitive League of Legends matches played in 2019. League of Legends is a very popular 5v5 multiplayer online battle arena (MOBA) game where each player has a different role and can choose strategically between different champions. Succeeding at killing the opponents and achieving objectives such as destroying towers or boosts by neutral monsters usually makes a team the winning one.

The objective of the project - besides the usual data cleaning process -  was to find out relationships or redundancies between features, as well as finding those that best predict the outcome of a game: victory or defeat.

Correlations between variables at team and individual player levels were compared and a generalized linear model (GLM) with a binomial error strucuture was used to identify the eleven most predictive variables.
These variables were selected using the Akaike Information Criterion (AIC).

Such a data-driven approach is both interesting for contesting, as well as confirming assumptions about which features/strategies are most important for winning based on domain knowledge about the game.

## Context of the project

This project was conducted as part of the coursework of my Masters degree (Management & Data Science) in the winter term 2019/2020 (October - March). The task was to analyze a self-chosen dataset using R and statistical methods of our choice and then explain the approach and results in a short report.

## How to run the code

The code is embedded in the R Markdown file where it is also annotated and explained.
Make sure you have the required libraries installed and have set the working directory. I used the R version 3.6.1.

## References
The data was obtained from https://oracleselixir.com/match-data/ for the competitive matches (excluding the world championship) in the spring and summer season of 2019.
