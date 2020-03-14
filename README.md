# Yelp_Review_Sentiment_Analysis
Prediction and  Sentiment Analysis of Yelp's Review Ratings



### Overwiew
The Yelp dataset has 10 columns and 10000 rows having no null values. The text in dataset is messy, so we have to clean the text. In text, we have to remove [stopswords](https://en.wikipedia.org/wiki/Stop_words) and punctuation.I have used logisctic Regression to get 92% accuracy. Even, Multinomial Naive Bayes also get ~91% accuracy on this dataset.

### Used Algorithm

- Logistic Regression 
- Logistic regression with use_idf=False/use_idf=True
- K-Nearest Neighbor
- Random Forest
- Decision Tree
- Multinomial Naive Bayes
- SVM

### Prerequisite

- Python (above 3.5)
- Sklearn
- Pandas
- Numpy
- nltk
