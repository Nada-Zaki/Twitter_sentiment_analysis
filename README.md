# Overview

I have used twitter dataset to classify the data into positive and negative tweets using a LSTM model with an initial embedding layer weights of a pre-trained word2vec model.




# Steps

1. Load dataset into the ipynb file (You can download the data from [here](https://www.kaggle.com/kazanova/sentiment140)).

2. Data preprocessing (remove punctuation, stop words, apply regex to remove certain patterns and map emojies to meaning words).

3. Apply tokenization, vectorization and padding (using nltk library).

4. Build a LSTM model for classification.

5. Download a [pre-trained google's word2vec model](https://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/) to appy on our model.

6. Train the model.

7. Test the model.
