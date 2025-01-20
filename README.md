# Trade Outcome Prediction Model for NFL Players

## Introduction
In recent years, sports analytics has gained traction as a powerful tool for enhancing strategic decision-making, not only among coaches and managers but also among fans and analysts. Trade events occur frequently throughout the year and are a crucial part of building a successful franchise. Teams consider many factors when trading players, such as the positions where they lack skill, the value of a player, and their potential. The variety of factors involved in trading players makes it challenging to predict trade outcomes. Currently, teams assess potential trade outcomes by looking at historical performance data, team needs, and player statistics to make informed decisions about which trades might contribute to future success. 

However, with the growth of machine learning and access to detailed statistics, it is now possible to build models that can predict the impact of a trade on a player’s performance. These models help us understand whether a player would work well with another team and how their performance might change based on the trade. 

This is exactly what we’ve done. By preprocessing historical NFL data, assigning scores to players by position, and aggregating them into team scores by position, we can visualize where teams are successful and where they lack skills in specific positions. We provide this information to our users, allowing them to make informed decisions when evaluating potential players. Our linear regression model then predicts how players will perform once they are traded for another player, offering a significant solution to the problem of predicting the potential outcomes of player trades.

## Our Dataset 
A public Kaggle dataset of player statistics from 2012-2023 contains 195 attributes related to individual player and team statistics. (Please refer to the link in the "Dataset Source" section at the bottom of the README).

---

## Files: 


Proposal-Ebya-Chaleas.pdf - Our team's proposal. 

CSCI-365 Final Project Pres..pptx - Our team's presentation file. 

final_nfl-potential-trade-analysis.ipynb - Our team's Kaggle notebook.

Final Report - NFL Potential Trade Analysis.pdf - Our team's final report. 

___

## Methods

### Data Preprocessing  
- Finding Our Dataset  
- Removing Outliers  
- Feature Selection  
- Min-max Normalization  

### Equations  
- Player Performance Score (PPS)  
- Team Position Score (TPS)  

### Data Visualization  
- Heatmap  

### Machine Learning Models  
- Linear Regression  

### Model Evaluation Metrics  
- R-Squared (\(R^2\))  
- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)

---

### Example Usage
Use the heatmap visualized in our Kaggle notebook to inform trade decisions. Then, simulate a trade by inputting two players to compare their predicted performance scores on their new teams.

---
## Video of Presentation: 
https://www.youtube.com/watch?v=WOEZEPdm62Y

## Dataset Source
Kaggle dataset used: https://www.kaggle.com/datasets/philiphyde1/nfl-stats-1999-2022?select=yearly_player_data.csv
