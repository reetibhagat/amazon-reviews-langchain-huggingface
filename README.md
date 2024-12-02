# amazon-reviews-langchain-huggingface
# Sentiment Analysis and Advanced NLP on Amazon Reviews

This repository showcases two approaches for analyzing Amazon reviews using Hugging Face's NLP models. It also integrates LangChain to demonstrate advanced workflows for chaining tasks like sentiment analysis and summarization.

## Files
1. **Sentiment_Analysis_on_Amazon_Reviews_with_Hugging_Face.ipynb**:
   - Basic sentiment analysis on Amazon reviews using Hugging Face's `transformers` and `datasets` libraries.
   - Ideal for users starting with NLP on structured datasets.

2. **Sentiment_Analysis_on_Amazon_Reviews_with_langchain_Hugging_Face.ipynb**:
   - Enhanced workflow using LangChain to perform advanced sentiment analysis and review summarization.
   - Demonstrates task chaining with pre-trained models for deeper insights.

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Python 3.7 or later
- Required libraries:
  pip install transformers datasets langchain langchain-huggingface
  
Key Features
Sentiment Analysis: Categorize Amazon reviews into positive or negative sentiments.
LangChain Integration: Use LangChain for task chaining (e.g., combining sentiment detection with summarization).
Dataset: Amazon Polarity dataset from Hugging Face's dataset hub.

Reference
This project was inspired by Hugging Face's blog post: Hugging Face + LangChain.
