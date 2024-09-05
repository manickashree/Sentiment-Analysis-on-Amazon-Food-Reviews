# Sentiment-Analysis-on-Amazon-Food-Reviews
Sentiment Analysis on Amazon Food Reviews


## Project Overview
This project performs sentiment analysis on Amazon food reviews using two different approaches: VADER (Valence Aware Dictionary and sEntiment Reasoner) and the RoBERTa pretrained model from Hugging Face. The objective is to compare the effectiveness of lexicon-based and transformer-based models in analyzing sentiment.

## Key Features
1. VADER Sentiment Analysis: A lexicon-based approach that assigns sentiment scores (positive, negative, neutral) using a "bag of words" method.
2. RoBERTa Sentiment Analysis: A transformer-based model that considers the context of words within sentences for a more nuanced understanding of sentiment.
3. Text Preprocessing: Tokenization, part-of-speech tagging, and named entity recognition (NER) were performed using NLTK to understand the grammatical structure and key entities in the reviews.
4. Comparative Analysis: Results from both VADER and RoBERTa were compared to understand the differences in sentiment prediction, highlighting the strengths and limitations of each approach.
## Libraries Used
1. NLTK: For text preprocessing (tokenization, POS tagging, and NER) and VADER sentiment analysis.
2. Hugging Face Transformers: For applying the RoBERTa pretrained model for context-aware sentiment analysis.
## Conclusion
This project illustrates the advantages of using transformer-based models like RoBERTa over simpler lexicon-based approaches like VADER, especially when context plays an important role in sentiment analysis. The results provide valuable insights into the importance of model selection based on the specific requirements of the task
