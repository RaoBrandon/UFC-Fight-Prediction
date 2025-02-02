## Project Overview
Is sports betting considered gambling? Many would argue that betting is a form of gambling, however it is important to note that, unlike most casino gambling, there are several metrics of interest that allow oddsmakers to set the lines on sports betting odds. Can we use the information available to us in MMA matches to come up with a prediction strategy that beats the odds? This is the key question I would like to begin to answer in the first iteration of this UFC MMA Data Science capstone project.

## Problem Statement
Many sport fans are looking for a method to support their favorite athletes by the form of placing bets on the outcome of their matches. While this is completely natural and expected, it may not be the most analytical approach to spending your money and in many cases going with that “gut feeling” can result in irresponsible spending on sports bets. In the interest of fun and entertainment (not practical financial advice) I would like to see if there is a criteria, we can put together that allows us to identify when our gut feeling might align with a potentially good bet within a reasonable margin of error (due to a certain degree of randomness of match outcomes). 

## Metrics
The main metric in use for this project is the prediction accuracy value of our model on the outcome of UFC fights as well as the cross validation score of our grid search. We are aiming to produce a more accurate prediction than the provided odds in the dataset without using them.

## Files & Instructions
- UFC-Fight-Prediction.ipynb
  - Main jupyter notebook project that cleans and preprocesses data, implements a Random Forest model, evaluates and provides takeaways
- ufc-master.csv
  - This file contains all UFC fight data that was used in the model training and prediction process
- upcoming.csv
  - Upcoming UFC fights as of the latest iteration of this dataset, motivation for a follow-up on this project is to apply the model in upcoming UFC fights

## Blog Post
This repository comes with an accompanying blog post, you can check it out [here](https://medium.com/@brandonrao123/i-out-predicted-ufc-oddsmakers-by-21-4b337aa9fbde).

## Licensing and Credits
Dataset courtesy of kaggle.com, check it out [here](https://www.kaggle.com/datasets/mdabbert/ultimate-ufc-dataset).
