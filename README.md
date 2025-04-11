# Analysing-Car-reviews-with-LLM

Overview
This project demonstrates how to analyze customer car reviews using Large Language Models (LLMs) and transformer-based pipelines. By leveraging advanced NLP techniques, the project performs sentiment analysis, translation, question answering, and text summarization on car reviews.

Features
1. Sentiment Analysis: Classifies car reviews as positive or negative using the distilbert-base-uncased-finetuned-sst-2-english transformer.
2. Translation: Translates car reviews from English to Spanish using the Helsinki-NLP/opus-mt-en-es transformer.
3. Question Answering: Extracts specific insights from car reviews using the deepset/minilm-uncased-squad2 transformer.
4. Summarization: Summarizes lengthy car reviews using the cnicu/t5-small-booksum transformer.

Metrics
The project evaluates model performance using:
1. Accuracy
2. F1 Score
3. BLEU Score 

Benefits
By analyzing unstructured customer feedback, this project provides actionable insights for improving car design and services. It also showcases how to optimize LLM inference for efficient deployment on limited hardware resources.
