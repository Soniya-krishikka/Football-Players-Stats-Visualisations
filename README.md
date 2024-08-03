# Football-Players-Stats-Visualisations

## Overview

This project analyzes football player performance data from 2015 to 2024. Using a dataset containing information about players, their matches, goals, assists, and season ratings, various visualizations and analyses are performed to uncover trends and insights. Key aspects include distributions of key metrics, player comparisons, team performance metrics, and more.

## Dataset

The dataset used in this project is `Latest Football Players 2024 Data.csv`, which contains the following columns:
- **Teams**: Team name
- **Seasons**: Season year or range
- **Players**: Player name
- **Matches**: Number of matches played
- **Goals**: Number of goals scored
- **Assists**: Number of assists made
- **Seasons Ratings**: Rating of the player's performance for the season

## Key Visualizations and Analyses

1. **Distribution of Matches Played**
   - Histogram showing the distribution of matches played by players.

2. **Distribution of Goals Scored**
   - Histogram illustrating the distribution of goals scored by players.

3. **Distribution of Assists Made**
   - Histogram depicting the distribution of assists made by players.

4. **Relationship between Matches and Goals**
   - Scatter plot to explore the relationship between the number of matches played and goals scored, colored by season ratings.

5. **Average Season Ratings by Team**
   - Bar plot showing the average season ratings for each team.

6. **Top Players by Season**
   - Bar plot identifying the top-performing players each season based on their ratings.

7. **Messi vs Ronaldo**
   - Line plots comparing Lionel Messi and Cristiano Ronaldo's performance metrics (ratings, goals, and assists) over time.

8. **Numeric Feature Correlations**
   - Heatmap of correlations between numeric features such as goals, assists, matches, and season ratings.

9. **Team Performance Metrics**
   - Bar plots displaying top teams by total goals, assists, and average season ratings.

10. **Team Performance Trends Over Time**
    - Line plots showing performance trends over time for top teams, including goals and assists.

11. **Top Teams by Goal-to-Match Ratio**
    - Bar plot of the goal-to-match ratio for the top teams.

## Setup

1. **Dependencies**
   - pandas
   - matplotlib
   - seaborn

   Install the required libraries using pip:
   ```bash
   pip install pandas matplotlib seaborn
   ```

2. **Data File**
   - Download the dataset and place it in the `/kaggle/input/football-players-datasets-2015-2024/` directory.

## Usage

1. **Load the Data**
   - Read the dataset into a pandas DataFrame:
     ```python
     import pandas as pd
     df = pd.read_csv('/kaggle/input/football-players-datasets-2015-2024/Latest Football  Players 2024 Data.csv')
     ```

2. **Generate Visualizations**
   - Execute the provided code to generate visualizations and analyze the data.
