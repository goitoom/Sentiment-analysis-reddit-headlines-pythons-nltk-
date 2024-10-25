Sentiment Analysis on Nissan Leaf Cars

This project performs a sentiment analysis on user opinions and discussions about the Nissan Leaf, focusing on data from Reddit. Through text mining, sentiment analysis, and topic modeling, this study offers insights into the sentiments, themes, and key issues experienced by Nissan Leaf owners, contributing to the broader understanding of customer perspectives in the electric vehicle (EV) market.

Project Overview

The study employs Natural Language Processing (NLP) techniques to analyze Reddit discussions, capturing sentiment and identifying frequently discussed topics related to the Nissan Leaf. The dataset was compiled by extracting comments from highly relevant Reddit posts to ensure a comprehensive analysis of various factors such as affordability, reliability, range anxiety, and battery life.

Features

Data Collection: Scrapes Reddit posts using the PRAW library to collect user comments on the Nissan Leaf, with keywords like "Nissan Leaf," "electric car," and "affordable electric car."
Data Cleaning: Processes text data to remove irrelevant content, including usernames, URLs, punctuation, and special characters, to ensure accurate sentiment analysis.
Text Preprocessing: Uses tokenization and stopword removal via NLTK to retain meaningful words in the analysis.
Sentiment Analysis: Leverages VADER lexicon to classify sentiments as positive, negative, or neutral, providing insights into user attitudes.
Topic Modeling: Implements Latent Dirichlet Allocation (LDA) to identify common themes, such as battery life, financial aspects, and EV incentives, that users associate with the Nissan Leaf.
Exploratory Data Analysis (EDA)
The EDA process revealed that discussions around Nissan Leaf include prevalent terms like "battery," "charge," "range," and comparisons to models like Tesla’s Model 3. Bigrams and word clouds highlighted topics such as "miles range," "fast charge," and "road trip," reflecting user focus on the vehicle’s driving range and charging capabilities.

Installation

Clone the repository and install dependencies:

bash
Copy code
git clone <repository-url>
cd nissan-leaf-sentiment-analysis
pip install -r requirements.txt

The analysis reveals that users have a generally positive sentiment towards the Nissan Leaf, with most discussions highlighting affordability, battery performance, and charging infrastructure. However, there are concerns about battery life and range for long-distance trips. Topic modeling has identified key themes, such as financial incentives, charging stations, and EV reliability, providing insights for Nissan and other stakeholders to improve user experience.

Evaluation

The model’s performance metrics, including Silhouette and Perplexity scores, indicate moderate coherence, suggesting further refinements could improve topic clarity and model precision.

Conclusion

This sentiment analysis provides valuable insights into user opinions on the Nissan Leaf, supporting stakeholders in making informed decisions on product enhancements and customer engagement strategies. By identifying common user sentiments and concerns, Nissan and the EV industry can better address customer needs and accelerate the transition to sustainable transportation.
