# IBM_Recommendations
Project 3 for Udacity Data Scientist Nanodegree Course 

## Introduction
For this project the interactions that users have with articles on the IBM Watson Studio platform are analyzed. The task is to make recommendations for them about new articles based on the recommendation algorithm.

## Overview 

The notebook is divided into below parts:

### I. Exploratory Data Analysis

First explore the data, get confident with datasets. There are some basic, required questions to be answered about the data, which will be used throughout the rest of the notebook.

### II. Rank Based Recommendations

For ranking analize the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. 

### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, look at users that are similar in terms of the items they have interacted with. 
These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

### IV. Matrix Factorization

Finally, complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. 
Using our decomposition, we will get an idea of how well we can predict new articles an individual might interact with.
Response on the results provided at the end.
