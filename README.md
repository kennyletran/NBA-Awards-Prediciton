# NBA-Awards-Prediction
# Making Subjective NBA Awards Objective: Predicting NBA End-of-Season Awards with Statistics

This project implements machine learning and data analytics methodologies to predict winners of five individual, end-of-season NBA Awards. 

## Project Objective

The primary objective of this project is to create an objective prediction model for each of the 5 main NBA Awards: Most Valuable Player (MVP), 6MOY (6th Man of the Year), DPOY (Defensive Player of the Year), ROY (Rookie of the Year), and MIP (Most Improved Player).

## Model Algorithms and Methods Used
Linear Regression
Ridge Regression
Lasso Regression
Random Forest

## Technologies and Packages Used
R, Python, Jupyter Notebook
Python: NumPy, Pandas, Sklearn, Matplotlib, StatsModels API
R: dplyr, glmnet, stringi

## Pre-Filtered Datasets 
nbaStats[Year].csv
Unfiltered NBA player statistics from basketball-reference for the years 2010-2020

## Cleaned and Filtered Datasets 
update142.csv
2010-2020 stats for each eligible NBA player including their voting percentages for each award
roydata142.csv
2010-2020 stats for each eligible Rookie of the Year player
smoydata142.csv
2010-2020 stats for each eligible Sixth Man of the Year player
mip_stats.csv
2011 -2020 difference in stats from the previous season for each eligible Most Improved Player player
nba2021.csv
2021 stats for each player (used for MVP and DPOY) 
roy2021.csv
2021 stats for each eligible Rookie of the Year Player
smoy2021.csv
2021 Stats for each eligible 6th Man of the Year Player
mip2021.csv
Difference between 2021 and 2020 stats for each player up until 5/12/2021 (used for MIP) 

## Usage
The following steps should be taken to run the four regression models:
Start with The NBA Awards Data Cleaning file 
Contains a step-by-step guide on the process and tools used to clean the data, including string manipulation, filtering, and handling missing variables. It can be run by downloading the nbaStats[Year].csvs. 
Create MIP data 
MIP Creation file provides the code for this 
Choose your fighter (model), and load the data in (all the files includes commented code explaining each part): 
Linear Regression: Linear Regression.ipynb
Random Forest: RandomForests.ipynb
Lasso + Ridge Regression: Lasso + Ridge Models.Rmd

## Contributors
Nilay Agarwalla, Raj Dasani, Bikram Khaira, Kenny Tran, Sarah Truong

## Resources
All data for 2020 (For all datasets, change the year in the URL to get different years): 
Player Data:https://www.basketball-reference.com/leagues/NBA_2020_per_game.html 
Voting Shares: https://www.basketball-reference.com/awards/awards_2020.html
