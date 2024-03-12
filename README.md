# EPL Analysis Project

## Introduction

The aim of this project is to explore the potential relationship between a football player's popularity and his market value in the English Premier League (EPL). The analysis also includes some interesting observations about players and the top 6 teams.

## Data Sources

The dataset for this project has been taken from the Kaggle. It includes information about all players listed on the FPL site for each team, along with their corresponding market values. Notably, players without a market value on transfermrkt.com, such as Scott McTominay, are excluded from the dataset.

The dataset is comprehensive, covering all players competing in the Premier League during the 17/18 season. The data is confirmed until roughly 20th July, including some new transfers.

## Preliminary Analysis

### Most Valuable Players

The project starts with identifying the most valuable players in the EPL based on market value.

### Most Popular Players

Next, the analysis looks into the players with the highest popularity, measured by page views.

### Distributions of Market Value and Popularity

The distributions of market value and popularity are visualized, with a focus on differences between the top 6 clubs and the rest of the teams.

## Detailed Analysis

### FPL Valuation

An examination of the relationship between Fantasy Premier League (FPL) valuation and market value, providing insights into player valuation metrics.

### Market Value with Age

Analyzing how player market value varies with age, considering the non-linear nature of this relationship.

### Top 6 Positional Strength

Investigating the positional strength of the top 6 clubs in terms of market value.

### Popularity as a Proxy for Ability

Exploring whether popularity, as measured by Wikipedia page views, can serve as a proxy for a player's ability, specifically using FPL valuation as a benchmark.

## Regression Model

Building a regression model to test the hypothesis that market value can be determined using popularity as a proxy for ability. The model includes factors such as age, position, and region.

## Residual Analysis

Examining residual plots to evaluate the model's performance and checking for heteroscedasticity.

## EPL Popularity Comparison

Comparing the popularity of the EPL with other leagues, utilizing the developed regression model.

## Conclusion

This README provides an overview of the EPL Analysis project, summarizing its objectives, data sources, and key findings. For more details, refer to the project's documentation and code files.

