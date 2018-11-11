
## Project Title

Text Mining of English Tweets in Nepal between 2015/5 to 2016/4

## Tools

SQL, Python, NLTK, R, a cloud computing platform hosted by University of Missouri.

## Data

English Tweets in Nepal between 2015/5 to 2016/4 were analyzed by various Text Mining methods.

## Data Exploratory

Two most mentioned terms in this period were “earthquake” and “India”, which corresponded to two major events occurred in Nepal: (1) The earthquake on May 12th, 2015 and (2) The blockage due to Nepal-India crisis on Sep 23rd, 2015. 
Five most influential tweeter users were identified by counting the number of retweets. 

## Sentiment Analysis & Modeling

Sentiment scores of the tweets were calculated by the “Vader” package in the NLTK library. 
Four models (Decision Tree, Linear Regression, Naïve Bayes, Support Vector Machine) were built to model the sentiment scores based on features of tweets, including time, the numbers of followers and following, the number of favorites, the lengths of tweets, the lengths of hashtags, and relative positions of hashtags. 
The decision tree model outperformed other models. 
The tweets sent by influencers were more dispersed in sentiment scores.

## Instruction

1. "data_carpentry_exploration.ipynb" contains all the codes for data carpentry and exploratory analysis with visualizations. 

2. "data_modeling.ipynb" contains all the codes for data modeling for my research question.

3. "sentiment_analysis.pptx" has the information for social media sentiment analysis and Vader sentiment package.

4. "merged_subsample_sentiment.csv" is the data set I got after data carpentry and it is used in data modeling.

5. The tweet table is very huge and the queries are slow. If you want to run the code cells by yourself please run them one by one and do not run them all together.
