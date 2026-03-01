# NBA Player Performance Analysis
### Understanding Role, Usage, and Statistical Production in the NBA

## Project Overview

This project analyzes NBA player performance data to understand the main drivers in scoring through data scraping, cleaning, feature engineering, statistical calculation and visualization. The main objectives are listed below;

- Identify the strongest factors that contributes mostly to scoring.
- Examine how playing time, total rebounds, turnover, etc. influences player statistics.
- Compare performance based on player positions.
- Dtermine whether scoring is driven more by usage or efficiency.

## Data Collection (Web Scraping)

- Source: Dataset was collected directly from Basketball Reference using Selenium.
- Link: https://www.basketball-reference.com/leagues/NBA_2025_per_game.html
- Size: 566 players
- Total rows: 566
- Total columns: 31
- Key variables: 
    - Player
    - Age
    - Pos: Position (PG, SG, SF, PF, C)
    - MP: Minutes played per game
    - FG: Field Goals
    - FGA: Field Goal attempts
    - FG%: Field Goal percentage
    - 2-Point Shooting: 3P, 3PA
    - 2-Point Shooting: 2P, 2PA
    - eFG%: Effective Field Goal Percentage
    - Free Throws: FT, FTA, FT%
    - Rebounds: ORB, DRB, TRB
    - Playmanking & Defense: AST, STL, BLK, TOV, PF
    - Scoring: PTS (Points per game)
    - Awards

## Tools & Technologies Used
- Python
- Selenium (web scraping)
- Pandas (data manipulation)
- Numpy
- Matplotlib
- Seaborn
- Plotly Express

## Skills Demonstrated
- Web Scraping
- Data cleaning and processing
- Feature engineering
- Correlation analysis
- Data normalization (per-minute metrics)
- Visualization (static + interactive)
- Analytical storytelling

## Analysis Roadmap
1. Thorough understanding the data
2. Data Cleaning
3. Exploratory Data Analysis
4. Correlation Analysis
5. Feature Engineering
6. Positional Analysis

## Key Findings
- The age distribution graph shows that most of the playes are of age between 22 and 28 years, highest in between 23 and 24 years. The peak performance is between 23 and 27 years.
- Scoring is different based on positions. Players playing as center have more average 2 point field goals, reflecting their interior role. Whereas, shooting guards and point guards show higher proportion of scoring from 3-points shots.
- Scoring is highly influenced by the minutes played (Correlation MP vs PTS = 0.88).
- Scoring is also strongly associated with offensive usage. High scorers also have high assists and turnovers.
- The top five scorer are Shai Gilgeous-Alexander, Giannis, Jokic, Luka, and Edwards.
- Rebounding is role-based and dominated by interior players.
- Interior players contribute more to both rebounding and scoring.
- More minutes played aslo means increase in personal fouls and defensive responsibility.
- Efficiency is less influential than opportunity.

## Final Conclusion
This project demonstrates that NBA statistical production is primarily driven by:
- Minutes played
- Offensive usage
- Player role
Scoring correlates strongly with opportunity and ball involvement rather than purely shooting efficiency. 

## Visualization

![Age%20Distribution.png](attachment:Age%20Distribution.png)

![Scatterplot%20of%20Total%20rebounds%20with%202P%20and%203P%20Field%20goals.png](attachment:Scatterplot%20of%20Total%20rebounds%20with%202P%20and%203P%20Field%20goals.png)

![Average%20Scoring%20Composition%20by%20Position.png](attachment:Average%20Scoring%20Composition%20by%20Position.png)


![Top%2025%20players%20by%20point%20per%20minute.png](attachment:Top%2025%20players%20by%20point%20per%20minute.png)

![Players%20with%20Highest%20Personal%20Foul.png](attachment:Players%20with%20Highest%20Personal%20Foul.png)

![Correlation%20Heatmap%20%28Non-Mechanical%20Metrics%29.png](attachment:Correlation%20Heatmap%20%28Non-Mechanical%20Metrics%29.png)


```python

```
