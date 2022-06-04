# recommendations-with-IBM

## Project motivation

In the IBM Watson Studio, there is a large collaborative community ecosystem of articles, datasets, notebooks, and other A.I. and ML. assets. Users of the system interact with all of this. Within this scope, we created this recommendation system project to enhance the user experience and connect them with assets. This personalizes the experience for each user.

## Inroduction:

To analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles you think they will like.

### The Project focuses the the following tasks:

I. Exploratory Data Analysis

Before making recommendations of any kind, we explore the data you are working with for the project. We answered some basic question about the data that were useful in the later parts of the project.

II. Rank Based Recommendations

Return the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You can complete a content based recommendation system, but i did not do it as a part of this project.

V. Matrix Factorization

Finally, a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition,  get an idea of how well it can predict new articles an individual might interact with (spoiler alert - it isn't great). Finally we discuss which methods I might use moving forward, and how you might test how well your recommendations are working for engaging users.

## Repository structure:

The important files in the repository that you will be directly working with are as follows:

  - data (description for both of these files are in the notebook)
    - articles_community.csv
    - user-item-interaction.csv 
  - Recommendations_with_IBM.ipynb (consists of the recommendation system and other necessary discussions)

All other files are either pickle files that will be later used in the jupyter notebook or are test files to check if we are going in the right direction.

## Other tasks:

- Deploy this system
- And compete the content based recommendation system based task.


