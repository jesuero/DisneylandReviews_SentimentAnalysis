## 🎡 Disneyland Reviews Sentiment Analysis

The aim of this project is to analyze the different Disneyland reviews classified according to their degree of satisfaction and to elaborate sentiment analysis algorithms so that, given a customer review, it is possible to know whether their degree of satisfaction is good or bad.

The dataset includes 42,000 reviews of 3 Disneyland branches - Paris, California and Hong Kong, posted by visitors on Trip Advisor.
 
Column Description:

- **Review_ID**: unique id given to each review
- **Rating**: ranging from 1 (unsatisfied) to 5 (satisfied)
- **Year_Month**: when the reviewer visited the theme park
- **Reviewer_Location**: country of origin of visitor
- **Review_Text**: comments made by visitor
- **Disneyland_Branch**: location of Disneyland Park

The dataset was downloaded from Kaggle and is availabele on this link: https://www.kaggle.com/datasets/arushchillar/disneyland-reviews


# Project phases

## 1. Exploratory Data Analysis

In this notebook, the dataset is explored to figure out some informative insights about Disneyland extracting some conclusions from the customers reviews.

## 2. Machine Learning Sentiment Analysis (TF-IDF, Bag of Words, Textblob)

In this notebook Sentiment Analysis is done for the Disneyland reviews dataset using different Machine Learning techniques. The notebook includes a text pre-processing step, Bag of Words and TF-idf models with Logistic Regression and Multinomial Naive Bayes and the use of TextBlob library pre-trained sentiment model.

## 3. Sentiment Analysis Deep Learning - LSTM & Dense 

Here, Sentiment Analysis model is built using Deep Learning. A model is develop after texting different parameters and architectures using and LSTM layer and predicting 'positive' or 'negative' for each review.

Then a predict is executed for all the reviews in the dataset in order to classify them and analyse the results.

## 4. Analysis of Results

In this notebook, the results obtained in the LSTM model are analysed. To do so, the predictions of the model will be analyzed and it will be seen if there are dependencies in the quality of its prediction with the rest of the variables.
Also, some insights are extracted from the data and its sentiment associated with the variables.
