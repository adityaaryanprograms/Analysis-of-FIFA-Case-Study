# Analysis of FIFA Case Study

## Problem Statement
We are told of the introduction of a new football club named ‘Brussels United FC’. It does not yet have a team. As the Data Science Team, we are given the task to use a data-based approach for the construction of a report which would help recommend players for the main team of the club. Fifteen players are required for the formation of the team. The budget for hiring of the players is fixed. The management wants to choose from a total of twenty possible players with potential. For the job, we are provided with a large data of players acquired through FIFA.

## Description
There are 25,490 records and a total of 60 columns in the data. For ‘Wage’, 'Release Clause’ and ‘Value’ columns, a function was defined to convert ‘K’ and 'M’ into 1000 and 1000000 respectively. For ‘Joined’ and ‘Contract Valid Until’ columns which had complete dates in some or all rows, last 4 characters of the values were taken and converted into int datatype using apply() function. For ‘Height’ column split() method was used to get foot and inches separately and then the values were converted to foot. Much more pre-processing and statistical analysis were done to recommend players for the main team.

## Outcome
Considered various physical, financial and psychological factors of all the players and how they affect their overall scores and ratings to recommend 20 players for the main team of the club ‘Brussels United FC’ from the large data of players. Also found out the top 5 players by overall rating for each unique position, finding the average wage one can expect to pay for them, as additional choices.

## Key Skills Used
Pandas, Pre-processing, Variable Analysis, Hypothesis Testing, Exploratory Data Analysis, NumPy, Python, Data Wrangling, Statistics, Analytical Skills, Pandas
