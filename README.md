# NHL-Shift-Project
This project gathers the average shift and scoring data during the 2019-2020 NHL regular season, and analyzes their relationship with Poisson regression.

Situational Shifts.Rmd - Parses through shift charts for each game from the NHL API to get the total amount of time each team spent at a certain strength during the 2019-2020 regular season, total number of shifts their skaters had, and the aggregate time their skaters were on the ice. From there computes each team's average shift time at each strength, and number of goals each team scored and allowed at each strength during the season. 

Analyzing Shifts.Rmd - Applies Poisson regression to each team's average shift time versus the number of goals they scored or allowed per 60 minutes of gametime to see if the average amount of time a team's skaters stay on the ice has a relationship with the scoring or defensive rates in the NHL.

Goals For by Strength 19-20.xlsx - Excel file acquired from nhl.com for the number of goals each team scored in the 2019-2020 regular season, broken down by the manpower situation of in the game the goal was scored.

Goals Against by Strength 19-20.xlsx - Excel file from nhl.com for the number of goals each team allowed in the 2019-2020 regular season, broken down by the manpower situation in the game when the goal was allowed.
