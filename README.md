# Classifier-project
This repository gives a neural model for reviews classification using torch
first the data analysis part is done 
analysized the review text with word tokenize and sentence tokenizer from NLTK library
labeled the rating as postive - 0 , negative - 1 ad moderate -2
for the SentimentAnalyzer.py , I used torch ,torchvision
defined a train test split function
defined a LSTM model
parameter are : vocab_size = len(train_tensor ,output_size = 1 , embedding_dim = 400  , hidden_dim = 1024 ,n_layers = 2
batch_size = 512.
