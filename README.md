# NBA MVP Prediction

## Introduction
The National Basketball Association (NBA) is a professional basketball league in North America comprising 30 franchises, of which 29 are in the United States and one in Canada. The league has grown from its humble beginnings to a global enterprise generating in excess of $8 billion in annual revenue. A major component to the rise in popularity of the sport has been directly attributed to the aggressive player centric marketing initiative. Fans often discuss and debate the accolades of specific players with greater passion than they do for the franchises they represent. 

The league does a tremendous job of staying ahead of the curve in terms of advanced analytics, but when deciding the most valuable player (MVP), they leave everything to the opinions of 100 NBA selected media members. Additionally, the league does not provide any criteria in the selection or voting process. Without a defined criterion, the argument for MVP is debated year after year. The purpose of this project is to see if there is an unwritten criterion that is being followed, and once determined, can it be used to predict future MVPs.

## Research Questions
1.	Are there any correlations between the variables?
2.	Which variables play the greatest effect on the vote?
3.	Does scoring average outweigh variables in the selection?
4.	Once the data is normalized, can it be seen that opinion outweighs statistical performance?
5.	Will a linear or non-linear approach produce a better result?
6.	What is the accuracy of the model? 

## Approach
The data to evaluate is expansive, so scaling down to specific variables is necessary. While data is available since the 1950 season, for purposes of the project, this model will be looking at data points over the past 10 seasons to determine correlations and variable weights.

## Data
The main datasets used in this project are: 
https://www.kaggle.com/lancharro5/seasons-stats-50-19#Seasons_stats_complete.csv - This dataset contains all the player statistics from 1950 – 2019. The season from 2010-2019 will be the focus. Additionally, offensive statistics will be the concentration of the analysis.

https://www.basketball-reference.com/awards/mvp.html#mvp_NBA::none – List of all previous MVP by season.

https://www.basketball-reference.com/leagues/NBA_2020_per_game.html - Current season stats to date.
