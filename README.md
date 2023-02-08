# NLP_Disaster_Tweets_Classification 

### 1.1 Problem 

Twitter is one of social media that has become an important communication channel in different situations, for instance, in times of emergency. The smartphones enable people to announce an emergency they see in real-time. Because of that, there is an challenge that how to recognize whether a tweet text is talking about a real disaster or uses those keywords as a metaphor, which can lead to huge mislabeling of tweets. Hence, this project aims
on using Natural Language Processing (NLP) and classification models to distinguish between real and fake disaster tweets.  

To do this, first, we will inspect, visualize, clean and vectorize the data then split train data into train_df (85%) and valid_df (15%) and train three models:  

(1) Long Short Term Memory (LSTM)  
(2) Bidirectional Long Short Term Memory (Bi-LSTM) 
(3) Gated Recurrent Unit (GRU)

Then, I will compare these three deep learning models by validation accuracy score and tune hyperparmeter (dropout) to get the best model and use this best model for predicting test data and print out the submission file.

Reference Source:   
(1) https://www.kaggle.com/code/philculliton/nlp-getting-started-tutorial/notebook  
(2) https://medium.com/mlearning-ai/the-classification-of-text-messages-using-lstm-bi-lstm-and-gru-f79b207f90ad  

### 1.2 Data 

In this project, I use data from Kaggle, were downloaded from the link:     
https://www.kaggle.com/competitions/nlp-getting-started/data

There are two data from this resource, included train and test data. Train data has 7613 observations and 5 columns included : id, keyword, location, text and target. Test data has 3263 observations and 4 columns included: id, keyword, location and text.
