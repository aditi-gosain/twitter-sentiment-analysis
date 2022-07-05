# twitter-sentiment-analysis

Sentiment Analysis is the method to measure attitude and emotions of a speaker/writer based on computational treatment of text data. Sentiment analysis could be performed in Python using 2 methods:

1) Calculating polarity and subjectivity using the library Textblob
2) Using senimentIntensityAnalyzer from the library vader

**Textblob**
Textblob sentiment analyzer returns two properties for a given input sentence:
Polarity is a float that lies between [-1,1], -1 indicates negative sentiment and +1 indicates positive sentiments.
Subjectivity is also a float that lies in the range of [0,1]. Subjective sentences generally refer to opinion, emotion, or judgment.

**Vader**
It uses a list of lexical features  which are labeled as positive or negative according to their semantic orientation to calculate the text sentiment. Vader sentiment returns the probability of a given input sentence to be positive, negative, and neutral.

This project is created to carry out a comparative study of both the libraries, using tweets fetched from the Twitter API.
