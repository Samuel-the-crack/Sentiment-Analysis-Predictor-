# Sentiment-Analysis-Predictor
Building a Sentiment Predictor Using Multinomial Naive Bayes 

<p align = 'center'>
<img src = 'https://github.com/Samuel-the-crack/Sentiment-Predictor/blob/main/Picture/Sentiment%20Analysis.png' width = 950>

## A. Background 
Comment section is one of the factor to measure customer's satisfaction, so in this repository I try to make a sentiment predictor using Multinomial Naive Bayes. This model use a string input and give a dataframe of the input string and the sentiment prediction itself. 

**Requirements : Pandas, Numpy, Seaborn, Sklearn, matplotlib, and NLTK**
  
## B. Overview 
I divided this model into three parts, first data preprocesing (missing value and duplicate value), second was string processing using NLTK, and third was data training.
The first part was removing the missing value, and duplicate value. For the string processing using NLTK there are two process, tokenizing and stemming. after the string data was processed, I vectorize using [CountVectorizer](https://towardsdatascience.com/basics-of-countvectorizer-e26677900f9c) to make it processable in model training. 
