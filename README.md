# Game Recomender System
## Steam Content-Based RS
![into](images/social-og.jpg)

## Introduction
As the gaming industry continues to experience rapid growth, driven by the vast array of games available worldwide, the sheer abundance of options presents a challenge for gamers in selecting which game to play. In response to this, global gaming companies would benefit from creating powerful game recommender systems tailored to users' interests amidst the overwhelming array of choices. 
The implementation of recommender systems by companies has proven to be highly relevant in driving increased sales and enhancing customer satisfaction. By offering personalized recommendations and tailored offers, companies can effectively attract and retain customers. For instance, sending targeted emails with links to new offers or suggestions for movies and TV shows based on individual preferences can significantly engage customers and foster loyalty.
____

## Implemented tasks
+ Analyze data from Steam, SteamSpy, and Metacritic services to form a dataset.
+ Develop a recommender system based on content-based filtering using the created dataset.
+ Deploy the finished recommender system on Streamlit app.
+ Evaluate the effectiveness of the obtained model.
____

## Content-based filtering (Recommender System itself)
A **recommender system**, as the name suggests, is a type of machine learning system that provides personalized recommendations to users based on their past behaviors, preferences, and patterns.

**Content-based filtering** customizes suggestions based on user interactions by analyzing characteristics and keywords connected to items in a database. It correlates them with a user’s profile formed from their activities such as purchases, ratings, searches, and clicks. By concentrating on individual preferences, content-based filtering delivers tailored recommendations that match each user’s unique tastes and interests.

**Advantages:**
+ This model operates independently, requiring no data from users.
+ Scalability is effortless, even with large user bases.
+ Highly relevant recommendations foster user trust and engagement, as user perceive the suggestions as personalized and pertinent.
+ By circumventing the “cold start” problem, content-based filtering mitigates the challenge faced by collaborative filtering in nascent communities or platforms with limited user data.
**Disadvantages:**
+ Recommendations are limited to the user’s established interests, lacking ability to introduce novel or diverse suggestions.
+ Scalability presents a hurdle, as every addition of a new product, service, or content necessitates meticulous attribute identification and tagging.
+ Inaccuracies and inconsistencies in attribute assignment may arise, potentially leading to flawed recommendations or user dissatisfaction.
