
## Database and Description
The VNL2023 dataset was obtained from Kagle (https://www.kaggle.com/) and contains detailed performance statistics for all players who took part in the 2023 Volleyball Nations League (VNL). The VNL is an annual international men’s and women’s volleyball tournament organized by the FIVB, featuring the world’s top national teams competing over several weeks in different host cities.

This dataset includes:
- **Demographic information**:  
  - Player age  
  - Country represented  
  - Team position (setter, outside hitter, middle blocker, libero)

- **Individual performance metrics (average per match)**:  
  - Attack points  
  - Service (ace) points  
  - Block points  
  - Number of scoring sets (sets that resulted in at least one point)  
  - Digs (successful defensive plays against an opponent’s attack)  
  - Receptions (successful passes of opponent’s serve to the setter)

## Analysis Objectives

Using this dataset, we will highlight two types of statistics:

1. **Individual statistics**  
   – By selecting a specific metric, display a leaderboard ranking players according to that metric and an Histogram of the distribution of that metric among the players.

2. **Team (collective) statistics**  
   – By selecting a country, display an histogram of total of each statistics for that team and 2 leaderboards: ranking of the top scorers in the team (points with blocks + atacks + serves) and ranking of the top defenders in the team (digs + receives)
