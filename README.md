#Sentiment Analysis with Sarcasm Detection 

This repository implements sentiment analysis with a 5-class classification and sarcasm detection using DistilBERT from Hugging Face. The analysis is performed on the Amazon Customer Reviews dataset 
dataset:https://www.kaggle.com/datasets/bittlingmayer/amazonreviews/code

Sentiment Analysis Model:
5-class classification using a Sequential Neural Network.
Architecture includes an Embedding layer, LSTM layer, and Dense layers.

Sarcasm Detection Model:
Utilizes DistilBERT for sequence classification.
replace your Hugging face token with the current token (HF-Token)
Fine-tuned for sarcasm detection.

Additional Information:
This project is designed to analyze sentiment across five classes: Very Bad, Bad, Neutral, Good, Very Good.
Sarcasm detection enhances the sentiment analysis by identifying sarcastic content.
The Gradio interface is provided for easy testing of the model on custom reviews.
