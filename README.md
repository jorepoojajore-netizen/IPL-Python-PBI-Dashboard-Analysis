# 🏏 IPL 2022 Data Analysis

## 📌 Project Overview
This project focuses on analyzing the Indian Premier League (IPL) 2022 dataset using Python and data visualization libraries. It explores team performance, match results, toss decisions, player achievements, batting scores, and bowling performance through data analysis and visualizations.

## 🎯 Project Objectives
- Analyze IPL 2022 match data.
- Identify the most successful teams based on match wins.
- Analyze the relationship between toss winners and match winners.
- Find the highest victory margins.
- Understand teams' toss decisions.
- Analyze Player of the Match awards.
- Explore top scorers and their highest scores.
- Visualize team and player performance using charts.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Jupyter Notebook

## 📂 Dataset Information
The project uses the `IPL 2022.csv` dataset containing information about 74 matches and 20 columns.

### Important Dataset Columns
- `match_id` — Unique match identifier.
- `date` — Match date.
- `venue` — Stadium where the match was played.
- `team1` and `team2` — Competing teams.
- `stage` — Match stage.
- `toss_winner` — Team that won the toss.
- `toss_decision` — Decision to bat or field.
- `first_ings_score` — First innings score.
- `second_ings_score` — Second innings score.
- `match_winner` — Winning team.
- `won_by` — Victory type, such as runs or wickets.
- `margin` — Victory margin.
- `player_of_the_match` — Player receiving the award.
- `top_scorer` — Top scorer recorded for the match.
- `highscore` — Highest individual score recorded.
- `best_bowling` — Best bowler recorded.
- `best_bowling_figure` — Bowling figures.

## 📊 Analysis Performed

### 1. Data Exploration
- Imported the IPL 2022 dataset using Pandas.
- Examined the dataset's shape and structure.
- Used `data.info()` to inspect column names, data types, and non-null values.

### 2. Highest Victory Margins
- Analyzed matches won by runs.
- Grouped the data by match ID and match winner.
- Sorted the victory margins to identify the highest values.

### 3. Toss Winners vs Match Winners
- Compared toss winners with match winners.
- Identified teams that won both the toss and the match.

### 4. Most Successful IPL Teams
- Counted match wins for each team.
- Ranked teams based on their recorded victories.
- Created a bar chart using Seaborn to visualize team performance.

### 5. Best Bowling Performance
- Explored the `best_bowling` column.
- Created a Plotly bar chart to examine recorded bowling performances.

### 6. Player of the Match Analysis
- Analyzed the `player_of_the_match` column.
- Created interactive Plotly bar charts to explore player awards.

### 7. Toss Decision Analysis
- Examined how frequently teams chose to bat or field after winning the toss.
- Calculated the percentage distribution of toss decisions.
- Visualized the results using pie charts and bar charts.

### 8. Team-Wise Toss Decisions
- Grouped toss decisions by toss-winning team.
- Compared the number of times each team chose to bat or field.

### 9. Top Scorers in IPL 2022
- Analyzed top scorers and their recorded high scores.
- Created a Plotly bar chart to compare batting performances.

## 📈 Visualizations
The project includes the following visualizations:
- Team-wise match wins.
- Best bowling performances.
- Player of the Match awards.
- Toss decision percentages.
- Toss decision counts.
- Top scorers and their highest scores.

## 💡 Key Learnings
- Data loading and exploration using Pandas.
- Grouping and aggregating match data.
- Filtering and sorting datasets.
- Comparing team and player performance.
- Calculating percentages using NumPy.
- Creating charts using Matplotlib and Seaborn.
- Building interactive visualizations using Plotly.

## 🏆 Conclusion
This project demonstrates how Python can be used to analyze IPL 2022 cricket data and identify patterns in team performance, toss decisions, batting, bowling, and match outcomes. The visualizations make the results easier to understand and communicate.

## 👩‍💻 Author
**Pooja Janu Jore**# IPL-Python-PBI-Dashboard-Analysis
This dashboard contains all types IPL overview and analysis using Python and PBI
