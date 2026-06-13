---
layout: page
title: Spam/Ham Email Classifier
description: NLP-based binary classifier distinguishing spam from legitimate emails using feature engineering, logistic regression, and cross-validation
img: assets/img/spam_ham.jpg
importance: 3
category:
---

## Overview

This two-part project builds a binary classifier to distinguish spam (junk/bulk) emails from ham (legitimate) emails using a real-world dataset of 8,348 labeled emails from SpamAssassin. The goal was to engineer meaningful features from raw email text and train a model that generalizes well to unseen data.

## Part 1: Feature Engineering & Logistic Regression

- Processed and cleaned raw email text data, handling missing values and normalizing case
- Engineered text-based features from email subject lines and body content using bag-of-words representations
- Trained and evaluated a logistic regression classifier using `scikit-learn`
- Analyzed model performance and identified key words and patterns most predictive of spam

## Part 2: Model Building & Fine-tuning

- Designed and implemented a custom classification pipeline with self-selected features
- Applied cross-validation to minimize overfitting and tune model hyperparameters
- Generated and analyzed ROC curves to evaluate classifier performance across decision thresholds
- Performed predictions on 1,000 unlabeled test emails with a 97.5% accuracy
  
## Tools & Skills

`Python` · `pandas` · `NumPy` · `scikit-learn` · `NLP` · `feature engineering` · `logistic regression` · `cross-validation` · `ROC analysis` · `text classification`
