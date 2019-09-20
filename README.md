## 1. Market Basket Analysis
<br>
Market Basket Analysis is a process of finding the frequency of collections items in a large transaction database. This is done to determine the association and correlation between items. Apriori is one algorithm used for market basket analysis. Apriori is designed to operate on databases that contain transactions. Terminology of apriori algorithm include:
<br>
- Support: Indicator stating how often an item appears in a dataset.
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
2. code/Market Basket Analysis.ipynb: implementation of Apriori Algorithms
<br>
  
## 2. Collaborative Filtering - User Based
<br>
Collaborative Filtering is a process of filtering information by collecting ratings from someone (or can be called "word of mouth"). The main problem of collaborative filtering is predicting how well someone will like an item (in this case the movies) that he has never given an assessment based on a collection of preferences/assessments that have been done previously by the community/group of people.
<br>
<br>
Next is an implementation of collaborative filtering algorithm using python to find a list of movies recommendations to someone based on an assessment made by someone else.
<br>

### File List
1. dataset/Film.csv: input file
2. code/Collaborative Filtering.ipynb: implementation of Collaborative Filtering Algorithms
<br>

## 3. Content Based Recommender
<br>
Content Based Recommender is a process of recommend information using the background/description of the target user (in this case the movies). The items used are described as variables, for example: Nation, Rating, Duration, Genre and Year.
<br>
<br>
Then an implementation of the content based recommender algorithm using python to find a list of other movies recommendations that are similar to a movie based on the movie's Genre and Rating and also based on the film's Nation, Duration and Rating.
<br>

### File List
1. dataset/Film1.csv: input file
3. code/Conten Based Recommender.ipynb: implementation of Content Based Recommender Algorithms
<br>

## 4. Hybrid Recommender
<br>
Hybrid Recommender is a process of recommend information by combining collaborative filtering and content based recommender.
There are two systems suggested in hybrid Recommender, namely:
<br>
- Content Based -> Collaborative
<br>
- Collaborative -> Content Based
<br>
<br>
Furthermore, an implementation of the hybrid recommender algorithm using python to find a list of movies recommendation that can be watched based on the similarity between the movie with the other movies and based on the correlation between the person with the other people.
<br>

### File List
1. dataset/Film.csv: input file
2. dataset/Film1.csv: input file
3. code/Hybrid Recommender.ipynb: implementation of Hybrid Recommender Algorithm
<br>

## 5. A/B Testing
<br>
A/B Testing is a test to see if there is a statistically significant difference between the two versions (usually one version is used as a control variable and the other version is used as a experiment variable). A/B Testing is used in the business world to determine customer habits based on a data approach, not with intuition.
<br>
<br>
Next is an implementation of A/B Testing using python to find whether there is a significant difference from the number of views and  the number of clicks activities on company's website homepage between the two website homepage designs, namely control and experiment.
<br>

### File List
1. dataset/homepage_action.csv: input file
3. code/AB Testing.ipynb: implementation of AB Testing Algorithm
<br>
