# Project 3: Using NLP to classify Subreddits - r/WallStreetBets & r/Stocks

## Problem Statement:
- Are public forums a good choice for knowledge seeking investors to learn about investing? 

### Table of Contents:
1. Repository Overview
2. Data Dictionary
3. Notebooks
4. Recommendations
   
#### Repository Overview
1. Notebooks folder containing individual notebooks for data sourcing, exploratory data analysis, and modeling. 

2. Data folder containing subreddit data generated csv files 

3. .pdf presentation 

#### Data Dictionary
- subreddit: individual subreddit the post belongs to
- title: title of post
- selftext: text of post
- created_utc: time in which post was submitted
- pro_title: title stripped to text only
- pro_selftext: selftext stripped to text only
- lem_title: lemmatized pro_title 
- lem_selftext: lemmatized pro_selftext

#### Reccomendations

After analyzing text from 24,440 reddit postings, WallStreetBets is not a suitable forum for investing advice because of the erroneous postings that cover the forum.  Stocks, on the other hand showed promise for general investing tips and advice.

