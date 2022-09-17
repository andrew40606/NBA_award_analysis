# NBA Data Analysis and Prediction

Author: Hsien-Chih Wang, Yuyang Xiao

## Problem Setting
The NBA is the biggest and the most well-known basketball league in the world. Since basketball is a sport of scoring, the statistical data of all players in the league was carefully tracked by the NBA and saved on their website, which provides an opportunity for analysts to study the players and the sport itself. In the NBA, there are some major awards for players and teams, such as MVP, DPOY and ROY. In this project, we want to find the best model for the award candidates and the award winners, and finally produce a model that can be applied onto predicting the future award winners.

## Problem Definition
- For the MVP, DPOY, and ROY awards, is there a pattern that is based on stats?
- Who is going to be in the discussion of the MVP, DPOY and ROY awards this year?
- Who is going to be the awards winners?

## Data Sources
- https://github.com/gmalim/NBA_analysis
- https://www.basketball-reference.com/leagues/NBA_2022_advanced.html
- https://www.basketball-reference.com/leagues/NBA_2022_per_game.html

## Data Description
- Players’ basic stats (points, rebounds, assists, etc.) from 1999-2000 season to 2019-2020 season.
- Players’ advanced stats from 1999-2000 season to 2019-2020 season.
- Separated basic stats for all-star players (1999-2000 season to 2019-2020 season).
- Separated basic stats for rookies (1999-2000 season to 2019-2020 season).
- MVP, DPOY, ROY voting results from 1999-2000 season to 2019-2020 season.
- SMOY voting results for 2018-2019 season to 2019-2020 season.
- NBA team stats from 1999-2000 season to 2019-2020 season
\
\
Each dataset contains the data of every player involved in that category, e.g., every player in the league for player basic stats and every player who got at least a score in MVP voting for MVP voting result dataset, to name a few.

## Prediction Result
### NBA Awards 2021
#### NBA Most Valuable Player
- #### Predicted by neural network : 
    1. ***Nikola Jokic***
    2. *Giannis Antetokounmpo*
    3. *Luka Doncic*

- #### Predicted by Linear Regression : 
    1. ***Nikola Jokic***
    2. *Giannis Antetokounmpo*
    3. *Jayson Tatum*
    
#### NBA Defensive Player of the Year
- #### Predicted by neural network : 
    1. *Rudy Gobert*
    2. *Nikola Jokic*
    3. *Joel Embiid*

- #### Predicted by Random Forest : 
    1. *Rudy Gobert*
    2. *Joel Embiid*
    3. *Nikola Jokic*

#### NBA Rookie of the Year
- #### Predicted by neural network : 
    1. ***Scottie Barnes***
    2. *Evan Mobley*
    3. *Franz Wagner*

- #### Predicted by Linear Regression : 
    1. ***Scottie Barnes***
    2. *Evan Mobley*
    3. *Franz Wagner*