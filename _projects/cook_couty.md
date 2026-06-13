---
layout: page
title: Cook County Housing Price Prediction
description: EDA, feature engineering, and linear regression on 200K+ housing records from Cook County, Illinois
img: assets/img/cook_county.jpg
importance: 4
category: 
---

## Overview

This two-part project explores what can be learned from an extensive housing dataset embedded in a dense social context in Cook County, Illinois (the county where Chicago is located). The dataset contains over 500,000 records and 62 features, with the goal of predicting residential **sale prices** using linear regression.

## Part 1: Exploratory Data Analysis & Feature Engineering

- Investigated the granularity, provenance, and social context of the Cook County Assessor's Office (CCAO) dataset
- Performed EDA on 204,792 training observations using `pandas`, `matplotlib`, and `seaborn`
- Engineered new features and designed a custom error metric to replace RMSE for this setting
- Analyzed the implications of adding demographic features (race, income, occupation) on model fairness

**Key insight:** Proposed proximity to subway stations as a domain-specific feature for predicting housing prices in dense urban environments, drawing on personal context growing up in Shanghai.

## Part 2: Modeling & Analysis

- Built and fit a linear regression pipeline using `scikit-learn` on cleaned and engineered features
- Evaluated model error and analyzed residuals to identify systematic biases
- Considered the real-world implications of predictive modeling in the context of Cook County's history of racial discrimination in property taxation

## Tools & Skills

`Python` · `pandas` · `NumPy` · `scikit-learn` · `seaborn` · `matplotlib` · `feature engineering` · `linear regression` · `EDA`
