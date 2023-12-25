# Articles-Stance-Sentiment-Analysis

Sentiment and stance analysis of online articles and news about Israel-Hamas war.

Two different models were used to detect stance and sentiment for articles based on their titles. 
The base model we used for the stance detection is DeBERTa v3 model. 
This model is available on the transformers library on HuggingFace. 
For the sentiment analysis, we used the lexicon based model for English language, VADER, available via NLTK library.
