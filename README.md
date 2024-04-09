**# Sentiment Analysis with Recurrent Neural Networks (RNNs)**
**Overview**
This project aims to predict the sentiment (positive or negative) of textual reviews using deep learning techniques, Recurrent Neural Networks (RNNs). Sentiment analysis is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text, such as a review or comment.
**Dataset**
The dataset used for this project is available at UCI Machine Learning Repository(https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences). It consists of labeled textual reviews collected from various sources(e.g., IMDb, Yelp, Amazon).
**Data Preprocessing**
Tokenization: The textual data was tokenized to split the sentences into individual words.
Vocabulary Building: The fit_on_texts method was applied to build the vocabulary based on the training data.
Zero Padding: Zero padding was added to ensure that all sequences have the same length, necessary for input to the RNN model.
**Model Architecture**
The sentiment analysis model employs a simple Recurrent Neural Network (RNN) architecture. The RNN processes the sequences of words in the reviews and learns to classify the sentiment based on the patterns in the text data.


To run this Project on Your PC: 
> Download zip file of this Project
> Extract all the files in same folder
> Upload it to google colab or Jupyter notebook
> Run the Project
