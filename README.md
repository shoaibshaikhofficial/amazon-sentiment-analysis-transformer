Amazon Sentiment Analysis Using Transformer Models

This project explores sentiment analysis of Amazon product reviews using a mixed-methods approach that combines machine learning (RoBERTa transformer model) with qualitative thematic analysis. The aim is to uncover mismatches between textual sentiment and star ratings, and to analyze how metadata such as product category, price, and discount influence sentiment patterns.

**Project Overview**

The analysis leverages Natural Language Processing (NLP) to classify customer reviews as positive, negative, or neutral. It goes beyond traditional sentiment analysis by integrating quantitative model predictions with qualitative insights, providing a holistic understanding of customer perceptions.

**Objectives**

Perform automated sentiment classification using RoBERTa.

Identify mismatches between textual sentiment and customer ratings.

Examine the influence of product metadata (price, category, discount) on sentiment.

Conduct thematic analysis on selected samples to derive qualitative insights.

**Dataset**

The dataset consists of Amazon product reviews (electronics and consumer goods) containing:

Review text

Star ratings

Product category

Price and discount details

Review metadata (helpfulness, timestamp)

Note: Dataset was obtained for academic research and cleaned for analysis.

**Methods & Tools**

Language Model: RoBERTa (Transformer-based NLP model)

Libraries:

transformers, torch, pandas, numpy, matplotlib, seaborn, sklearn

Qualitative Analysis: Thematic coding using NVivo/manual tagging

Evaluation Metrics: Accuracy, F1-score, Confusion Matrix

**Usage**

Clone this repository

git clone https://github.com/yourusername/amazon-sentiment-analysis.git
cd amazon-sentiment-analysis


Install dependencies

pip install -r requirements.txt


Run the Jupyter notebook

jupyter notebook "Amazon Sentiment Analysis Code.ipynb"

**Results Summary**

RoBERTa achieved high accuracy in classifying sentiment with balanced performance across classes.

Discrepancies between textual sentiment and star ratings revealed subjectivity in customer perceptions.

Thematic analysis highlighted key factors influencing sentiment, such as delivery speed, product quality, and expectation mismatch.

**Technologies Used**

Python 3

Jupyter Notebook

Hugging Face Transformers

Scikit-learn

Pandas, NumPy, Matplotlib

**Academic Context**

This project was developed as part of a Master’s in Business Analytics dissertation, focusing on applying NLP and data analytics techniques to real-world e-commerce data.

**Author**

Shoaib Farid Shaikh
Master’s in Business Analytics
Ireland
GitHub Profile
