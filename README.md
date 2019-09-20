# Practise-Case-Applied-Machine-Learning-in-Marketing
## 1. Market Basket Analysis
<br>
Market Basket Analysis is a process of finding the frequency of collections items in a large transaction database. This is done to determine the association and correlation between items.
<br>
Apriori is one algorithm used for market basket analysis. Apriori is designed to operate on databases that contain transactions. Terminology of a priori algorithm include:
<br>
- Support: Indicator stating how often an item appears in a dataset
<br>
- Confidence: Indicator stating how often a rule found is true.
<br>
- Lift: The ratio value of the observed support value with the expectation if X and Y are free from each other.
<br>
<br>
Then implementation of apriori algorithm is done by using python to find the association of the items given.
<br>

### File List
1. dataset/Untitled form.csv: input file
2. code/Market Basket Analysis.ipynb: implementation of apriori algorithms
<br>
  
## 2. Collaborative Filtering - User Based
<br>
Collaborative Filtering is a process of filtering information by collecting ratings from someone (or can be called "word of mouth"). The main problem of collaborative filtering is predicting how well someone will like an item (in this case the movie) that he has never given an assessment based on a collection of preferences/assessments that have been done previously by the community/group of people.
<br>
<br>
Next is an implementation of collaborative filtering algorithm using python to find a list of film recommendations to someone based on an assessment made by someone else.
<br>

### File List
1. dataset/Film.csv: input file
2. code/Collaborative Filtering.ipynb: implementation of collaborative filtering algorithms
<br>

## 3. Content Based Recommender
<br>
Content-Based Recommender is a process of recommend information using the background/description of the target user (in this case the movie). The items used are described as variables, for example: Nation, Rating, Duration, Genre and Year.
<br>
<br>
Then an implementation of the content-based filtering algorithm uses python to find a list of other film recommendations that are similar to a film based on the film's Genre and Rating and also based on the film's Nation, Duration and Rating.
<br>

### File List
1. dataset/Film1.csv: input file
3. code/Collaborative Filtering.ipynb: implementation of content based algorithms
<br>

## 4. Hybrid Recommender

<br>
Hybrid Filtering is a process of recommend information by combining collaborative filtering and content-based filtering.
There are two systems suggested in hybrid filtering, namely:
<br>
- Content-Based -> Collaborative
<br>
- Collaborative -> Content-Based
<br>
<br>
Furthermore, an implementation of the hybrid filtering algorithm uses python to find a list of recommendations for other movies that have not been watched by a user. has similar to a movie that has been watched based on the film's Nation, Rating, Duration, Genre and Year and has a high correlation with other people.
<br>

### File List
1. dataset/Film.csv: input file
2. dataset/Film1.csv: input file
3. code/Collaborative Filtering.ipynb: implementation of hybrid recommender algorithms
<br>
