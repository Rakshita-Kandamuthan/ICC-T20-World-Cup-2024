
# ICC Men's T20 World Cup 2024 Matches Analysis

This repository contains Python code for analyzing the ICC Men's T20 World Cup 2024 matches dataset. The code performs various analyses and visualizations to derive insights from the data.

## Dataset

The dataset (matches.csv) includes information about each match played in the ICC Men's T20 World Cup 2024, including details such as match number, teams, dates, venues, toss details, match results, winning team, man of the match, and more.

## Dependencies
- Python 3.x
- Libraries: numpy, pandas, seaborn, matplotlib

## Analysis and Visualizations
### 1. Cleaning the Dataset:

The dataset is cleaned to handle missing values and convert data types where necessary (Date_of_match, Win_by_runs, Win_by_wickets). Cleaned data is saved to matches_cleaned.csv.
### 2. Number of Matches Won by Each Team:
A bar chart shows the number of matches won by each team    participating in the tournament.
### 3. Win Methods for Top Teams:
Shows how the top-performing teams achieved their wins (by runs or wickets) using a stacked bar chart.
### 4. Teams that Have Not Lost a Single Match:
Displays teams that have not lost any matches using a horizontal bar chart.
### 5. Impact of Toss Decision on Match Outcomes: 
Analyzes how the toss decision (batting or bowling) affects match outcomes using a bar chart.
### 6. Impact of Winning the Toss on Match Outcome:
Illustrates the impact of winning the toss on match outcomes using a pie chart. 
### 7. Match Outcome Over Time: 
Shows the distribution of match outcomes (played or not played) over time using a stacked area plot.
### 8. Winning Margins by Runs and Wickets:
Compares the average winning margins (by runs and wickets) for each team using a grouped bar chart.
### 9. Venue Performance Analysis:
Analyzes team performance across different venues using a heatmap, showing the number of wins per venue per team.
### 10. Man of the Match Awards:
Displays the number of times each player has won the Man of the Match award using a bar chart.

## Usage
1. Ensure Python and the required libraries are installed.
Download the matches.csv dataset and place it in the specified directory.

2. Run the Python script provided (analysis.py) to perform data cleaning, analysis, and generate visualizations.

3. The cleaned dataset (matches_cleaned.csv) and visualizations will be generated as specified in the script.

## Author
K Rakshita