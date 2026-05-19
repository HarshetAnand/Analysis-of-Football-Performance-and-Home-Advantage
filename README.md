# Exploring the Correlation between Skill Position Yards and Home Advantage on Football Game Outcomes

A statistical analysis project investigating how skill position performance and home-field advantage influence NFL game outcomes. Using regression analysis, hypothesis testing, and visualization techniques on 2019-2023 NFL data, this project quantifies the impact of various factors on game results.

## Research Question

Can we predict the outcome of NFL games based on team performance statistics when playing at home and the contribution of specific skill positions?

## Key Findings

- Home teams won statistically significantly more games than away teams from 2019-2023 (p-value = 0.019)
- Home teams average ~1 point more per game than away teams
- Quarterback passing yards strongly correlate with team success
- Different teams rely on different skill positions for offensive production
- Overtime games show no significant home advantage

## Methodology

- Regression analysis to identify relationships between yards, points, and wins
- Binary logistic regression for home advantage outcomes
- Confidence intervals and hypothesis testing on score differences
- Comparative visualizations across positions and seasons

## Tech Stack

- R (tidyverse, ggplot2)
- Statistical modeling
- Data visualization
- RMarkdown for reproducible analysis

## Dataset

NFL game-level statistics from 2019-2023 sourced from Advanced Sports Analytics, covering all offensive skill positions across every game.
