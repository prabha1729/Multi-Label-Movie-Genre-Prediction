# Predictive Analytics with Spark

# Project Description
- The objective of the project is to implement a movie genre prediction model using
Apache Spark
- The dataset provided [here](https://github.com/prabha1729/Multi-Label-Movie-Genre-Prediction/blob/master/train.csv) contains information about movies.
- train.csv has movie summaries of around 31K movies along with their genres. You will
use this to train your predictive analytics model
- test.csv has just plot summaries. You will be predicting the genre of these movies
- The task of predicting the genre is essentially a multi-label classification problem. A
movie can have multiple genres associated with it. Your model should be able to predict
all the genre associated with the movie
- The mapping of the genre to the string index should be generated in .csv format. For example
presence of genre ‘Drama’ is indicated by a ‘1’ in the first position of the prediction string
and an absence of this genre is indicated by ‘0 in the first position

## Basic Model (term-document matrix)

- Analyze the data and preprocess it if needed
- Create a machine learning model (use any algorithm) in spark to use the information
provided in the train set to predict the genres associated with a movie.
- You should create a term-document matrix from the plots and use these as feature
vectors for the machine learning model.

## TF-IDF to improve the model
- Focussing on the summary of the movie, implement Term Frequency-Inverse Document
Frequency (TF-IDF) based feature engineering technique to improve the performance of
the model
- Ideally, your model should improve performance from the previous step

## Feature Engineering (Word2vec)

- Implement any one of the modern text-based feature engineering methodology to
improve the performance of the model
- Custom feature engineering would be deemed successful only if the model performs
better than the model of part 2
