# Machine-Learning-Problems-Set-2-
# Climate Sentiment Analysis: Twitter vs News

## Project Overview
This repository contains the code and outputs for Machine Learning Problem Set #2: Using text as data. The project compares sentiment in climate change tweets and climate-related news articles using one lexicon-based baseline and two supervised text-classification approaches.

## Methods
This project uses three approaches:

1. AFINN-111 baseline
   - Lexicon-based sentiment scoring
   - Used to generate silver labels for the Twitter dataset

2. TF-IDF + Logistic Regression
   - Main supervised model
   - Uses bigram TF-IDF features and class-balanced logistic regression

3. LSA + Logistic Regression
   - Used to compare a denser semantic representation against sparse TF-IDF
