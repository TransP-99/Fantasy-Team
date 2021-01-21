# Fantasy-Team
INTRODUCTION:

A fantasy cricket team is a team of 11 players created for a match with a given budget and a set of rules to be followed. Contests are conducted with multiple users participating with their own fantasy teams. 
At the end of the match, each player is assigned with some points based on their individual performance in that match. The cumulative points made by the 11 players in the fantasy team is the user score. This is compared with the other participants to identify the winners. 

Linear programming is a method which involves optimising a mathematical function subject to certain constraints, where both the function and constraints are linear.

In this datacase, the concepts of linear programming is applied to create a fantasy cricket team.
DATASET:

This is a sample dataset prepared to pick the fantasy team for a match between Rajasthan & Kolkata. In the dataset, both the teams have played 7 matches. 

Each player's details in this tournament is available in the dataset. This information will be used to generate the fantasy team between the two teams.  

Syntax:
  z <- datasetName.describe()
  or
  z <- datasetName['Attrition_Flag'].describe()
  
#####

#   Function Name:  describe()
#   Usage:          Used to find summary statictics of variables
#   Syntax:         datasetName.describe() or datasetName['Attrition_Flag'].describe()
#   Additional Arguments :  datasetName is a pandas dataframe object. datasetName.describe(include='all') , datasetName.describe(include=[np.number]) , datasetName.describe(include=['category']) 
#   Output :         For numeric variables: count, mean, std, min, 1st quartile, median, 3rd quartile, max
#                   For factor variables: number of observations, number of unique values and value with maximum frequency

