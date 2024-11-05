# Natural Language Processing--Analysing Women-Clothing-Brand-Reviews

This project involves analyzing customer reviews for a clothing brand using Natural Language Processing (NLP) techniques. The goal is to extract insights from customer feedback, including identifying sentiment, key topics, and factors influencing customer recommendations. This README will walk you through the setup, data description, methods, and analysis performed.

**Table of Contents**

* Project Overview
* Dataset
* Dependencies
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* NLP Analysis
* Model Evaluation
* Results and Interpretation
How to Run
Future Improvements
Contributing
License

**Project Overview**

This project applies various NLP techniques to understand customer feedback for a clothing brand. By analyzing reviews, we aim to uncover insights into customer satisfaction, identify common themes, and perform sentiment analysis. These insights can help inform business decisions around product development, customer service, and marketing strategies.

**Dependencies**

* Pandas
* Numpy
* seaborn
* matplolib
* sklearn
* nltk
* string
* textblob
* wordcloud
* gensim

**Data Preprocessing**

Data preprocessing steps include:

* Renaming columns
* Cleaning Text: Removing special characters, numbers, and extra whitespace.
* Lowercasing: Converting all text to lowercase for consistency.
* Tokenization: Breaking down sentences into individual words.
* Stopword Removal: Removing common words that do not add value to the analysis.
* Lemmatization: Converting words to their root forms (e.g., "running" to "run").
* Handling Missing Values: Filling or dropping missing values as appropriate.

**Exploratory Data Analysis (EDA)**

Exploratory analysis was conducted to understand the distribution of:

Average rating corresponding to each product
Average rating and total number of customers corresponding to each product
Distribution of Ratings
Top Words: Identifying the most common words in positive and negative reviews.

**NLP Analysis**

**1. ## Sentiment Analysis with polarity**

* Using TextBlob, we performed sentiment analysis on each review to categorize them as positive, negative. This helps gauge overall customer sentiment towards products.
* Conducted sentiment analysis across various segments, including:

* Age Groups: Identifying sentiment trends in different age demographics.
* Sub categories: Analyzing sentiment by sub categories.
* Product Categories: Understanding sentiment by product type.
* Location: Analyzing sentiment by customer location.

**2. Word Clouds**

Word clouds for positive and negative reviews(based on rating)

**3.Perfom text mining**

To tasks to understand what most frequent words are used for positive sentiment and negative sentiment

**Perfom predictive analytics**

To understand the drivers of customers who are recommending the products

**. Topic Modeling**

Using techniques like Latent Dirichlet Allocation (LDA),created topics and understand themes behind the topics by performing topic mining

**Model Evaluation**

The NLP models and techniques were evaluated using:

Sentiment Accuracy: Cross-checking with actual recommendations to validate sentiment predictions.
Topic Coherence: Using coherence scores to evaluate the quality of topic modeling.
Word Cloud Validation: Cross-verifying word clouds against common topics identified in reviews.
Results and Interpretation


Key insights gained from the analysis include:

* Customer Satisfaction: Overall sentiment trends and specific factors driving satisfaction or dissatisfaction.
* Product Improvement: Identified areas where the brand could improve based on common negative feedback.
* Predictive analysis helped to understand the drivers of customers who are recommending the products










