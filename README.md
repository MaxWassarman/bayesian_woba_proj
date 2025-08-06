# Bayesian wOBA Projection Model
A Bayesian hierarchical model for projecting batter performance.

This project was developed for a private reading class in Bayesian data analysis. It implements a projection system that combines traditional sabermetric methods (Marcel projections) with modern Bayesian modeling techniques to predict batter wOBA (weighted On-Base Average).

All plots and results are included in the pdf and csv.

## Core Components

- 5/4/3 year weighting scheme for historical performance
- Regression to league mean based on plate appearance totals
- Simple attempt to capture players skills not represented in woba
- Player, season, and team random effects
- Natural splines for age adjustment

## Acknowledgments
Data Source: Fangraphs

Marcel Methodology: Tom Tango
