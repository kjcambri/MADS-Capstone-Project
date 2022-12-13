# Abstract

Around 20,000 soccer player records were extracted from https://sofifa.com with the goal to
predict the ideal soccer player position from player skills and attributes using machine learning
(ML). It was hypothesized that at least one model would differ from the baseline logistic
regression model. The initial data provided player positions based on the current 14 playing
positions. These were then encoded to represent one of four positions: midfield, defense,
forward, or goalkeeper. The dataset was split into a 70:30 train-test split ratio to evaluate model
performance amongst five different models: Logistic Regression, k-Means, Support Vector
Machine (SVM), Random Forest, and Stochastic Gradient Descent (SGD) Classifier. The
random forest model returned the highest accuracy score (93%) and highest recall score (93%).
This implies that the random forest model correctly classified the actual proportion of those in
their ideal position, on average, 93% of the time. For this reason, the random forest model was
recommended for classifying the ideal soccer player positions based on player skills and
attributes. Further development of this model include gaining insights from professional coaches
and expanding on the player database, as it would be beneficial in improving the model before
deploying it for professional soccer teams to use. This model benefits soccer teams and
franchises in gaining a return on investment with their players as it would improve overall team
and player performance. 

# Table Of Contents
  1. Business Background
  2. Problem Statement
  3. Scope of Analysis
  4. Approach
  5. Limitations
  6. Solution Details
  7. Concluding Summary
  9. Call to Action
  
# Business Background

Soccer is an international sport with participation from over 200 countries (Bundesliga,
n.d.). Each team has 11 players on the field that are placed in one of four types of positions:
forward, midfield, defender, or goalkeeper. Given soccer’s popularity, successful teams are
extremely profitable. For example, according to Ozanian (2021), Barcelona’s team is valued at
$4.76 billion USD, followed by Real Madrid at $4.75 billion USD. Kylian Mbappe is currently
the highest paid soccer player and will earn $63 million USD per year for the next three years
(Paul, 2022). Given the profitability of soccer, it is crucial that players are used correctly to bring
the team success and for investors to see a profitable return from their investment. Many soccer
teams collect statistics on their players, but currently, there is no known algorithm being
implemented to assess player stats and attributes to place players where they would best benefit
the team.

# Problem Statement

Team performance risks decline when players are not used to their strengths. This is
costly to the individual player, the team, and the franchise, given that teams with potential to
succeed fail to do so. Use of data analysis in most sports franchises has increased significantly,
given that most teams want a return on investment when signing contracts with players. The
current problem in soccer is that players are not being used to their potential to best improve
their overall team’s performance. 
The motivation behind this study was to contribute to teams in maximizing player
potential to better improve a team’s investment in players. This would help teams increase their
profitability and analytically place players to their strengths.

# Scope of Analysis

Elements that will be included within the analysis include non-redundant player statistics 
on their skills and attributes that are extracted from https://sofifa.com. To maintain consistency, 
data will not be extracted from any other website. Each datapoint represents one player that is 
currently or was registered as a player with the FIFA organization. The analysis will utilize five 
different models: Logistic Regression, k-Means, Support Vector Machine (SVM), Random 
Forest, and Stochastic Gradient Descent (SGD) Classifier. The model with the highest accuracy 
score and the highest average recall score would be the recommended model for utilization, 
given that it supports the hypothesis that it will differ from the outcome of the baseline logistic 
regression model. This analysis will not include data on how long players have been playing for 
in the league or any of their statistics from previous years. Given that the goal of the study was to
classify soccer players in their ideal positions from their measured skills and attributes, it was 
assumed that all players are currently playing in their ideal positions. Players are often traded or 
sold to different teams throughout the season and might be placed in different field positions. 
This would cause their overall stats to fluctuate. For this reason, this movement is expected to be 
captured by the models. 

# Limitations

Limitations to the current dataset and research include the limited time to extract data.
Additionally, the dataset included data of around 17,000 professional players, but they were not
organized by the time individuals spent playing soccer. For this reason, those who have spent
longer playing soccer might contribute to some skewness in the data. Lastly, although around
17,000 rows of player data were utilized, a historic measure of player data from previous years
were not considered, just the average statistics of the current season of all players with available
data.

# Solution Details

To further improve player placements, future modeling can consider classifying based on 
the specific field positions, which are based off the overall playing style positions, rather than 
general playing style positions alone. The next steps for this model include deploying it onto a 
web interface to classify players based on their skills and attributes in real time, as well as to 
continue to tune the model with new and updated data to further improve model performance.

# Concluding Summary

The Random Forest model was recommended for predicting soccer player positions
based on attribute data. The model demonstrates the potential in placing soccer players in
playing positions that suit their physical build and skills. Given that the modeling accuracy was
high, modeling would be insightful for professional teams to utilize when building their teams
and choosing players to invest in. Although modeling will provide meaningful insights to benefit
the team, modeling on player attributes alone might not be sufficient in determining ideal player

# Approach

The Random Forest model was recommended for predicting soccer player positions
based on attribute data. The model demonstrates the potential in placing soccer players in
playing positions that suit their physical build and skills. Given that the modeling accuracy was
high, modeling would be insightful for professional teams to utilize when building their teams
and choosing players to invest in. Although modeling will provide meaningful insights to benefit
the team, modeling on player attributes alone might not be sufficient in determining ideal player
positions. For example, overall team playing styles, coaching styles, and overall environment
might also affect a player’s ability to perform at their peak ability.

# Call to Action (CTA):
### Please reach out to:
#### Kevon Cambridge (kcambridge@sandiego.edu)
#### Payal B Muni (pmuni@sandiego.edu) 
#### Kevin Stewart (kevinstewart@sandiego.edu)


