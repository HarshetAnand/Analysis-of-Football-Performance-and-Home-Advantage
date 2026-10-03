# Exploring the Correlation between Skill Position Yards and Home Advantage on Football Game Outcomes

A statistical analysis project investigating how skill position performance and home-field advantage influence NFL game outcomes. Using hypothesis testing, confidence intervals, trend fitting, and visualization on 2019-2023 NFL data, this project quantifies the size of the home advantage and compares how teams use their skill positions.

## Research Question

Can we predict the outcome of NFL games based on team performance statistics when playing at home and the contribution of specific skill positions?

## Key Findings

- Home teams scored significantly more points than away teams from 2019-2023 (two-sample t-test, p = 0.019)
- Home teams averaged about 1 point more per game than away teams
- Home teams won more games than away teams in four of the five calendar years
- Quarterbacks and wide receivers account for most offensive yardage, while running back yardage declined slightly over the period
- Different teams rely on different skill positions for offensive production
- Overtime games show no clear home advantage

## Methodology

- Confidence intervals for mean home and away scores
- Two-sample t-test on the difference between home and away scores
- Scatter plots with fitted trend lines (linear, LOESS, and GAM) relating attempts, receptions, and yards by position
- Comparative visualizations across positions, teams, and seasons

## Tech Stack

- R (tidyverse, ggplot2)
- Statistical inference
- Data visualization
- RMarkdown for reproducible analysis

## Dataset

NFL game-level statistics from 2019-2023 sourced from Advanced Sports Analytics, covering all offensive skill positions across every game. The analysis reads `nfl_pass_rush_receive_raw_data.csv`, available at https://www.advancedsportsanalytics.com/nfl-raw-data.

## Files

- `Analysis of Football Performance and Home Advantage.Rmd`: the full analysis and write-up
- The PDF: the rendered report

Completed as a group project.
