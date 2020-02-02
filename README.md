# Create_Recommendation_Engine_With_IBM_Watson

### Introduction

For this project, I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like. Below you can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.
![](Example.png)

I. Exploratory Data Analysis

Before making recommendations I dived in the data to see what I can find. There are some basic, required questions to be answered about the data. 

II. Rank Based Recommendations

To get started in building recommendations, I first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Content Based Recommendations 

I was Using NLP techniques to find the the amount of content available for each article and improve the recommandations based on each articles' content.

V. Matrix Factorization

Finally, I completeed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix decomposition. Using the decomposition, I got an idea of how well I could predict new articles an individual might interact with (spoiler alert - it isn't great). I finally finally discussed which methods I might use moving forward, and how I might test how well my recommendations are working for engaging users.
