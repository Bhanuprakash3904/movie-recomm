# Movie Recommender System

## Overview
Let's assume you're interested in creating a recommendation engine to help recommend to users new movies based on previous ratings of movies they've watched. 

There are atleast two types of recommender systems you can build:

### 1. User Based Collaborative Filtering

> + The idea here is to build a matrix of users (rows) vs things they've bought/watched/browsed/rated (columns)
> + Compute similarity scores between users (rows) 
> + Find similar users to you
> + Recommend stuff they've bought/watched/browsed/rated that you haven't  

**Downsides**: 

+ Users can be nefarious
    + a user can spam by rating movies in a way to benefit their cause
+ People's taste and interest change over time
+ Far more users than things
  + Computationally very Slow
