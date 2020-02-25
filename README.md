# Classificaiton - a real disaster or not
* Disaster detection from twitter feed
* wild fire, accident, you name it! We will find out whether the tweets is indicative of a real disaster or not

## Datasource
https://www.kaggle.com/c/nlp-getting-started
* username eyyeung on Kaggle - E Yeung

## Apporach
* NLP - many to one problem
* TensorFlow Word Embedding, Convulution, LSTM, Dense

## Steps
1. get the data
2. inspect the data
3. clean up the tweets, stripping, pre-processing
    * need to shuffle the train data before splitting it into train and cross validation
4. decide what deep learning model to use
    * use tensorflow to do tokenization,embedding and dense layers
5. improve model using cross validation data
6. output the test data
7. submit

## Content
* input folder - contains the train and test sets
* output folder - contains the prediction for the test set
* Fake_or_real_NLP_TF_Embedding.ipynb - iPython notebook containins the code