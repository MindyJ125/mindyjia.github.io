---
layout: page
title: Spatial Telemetry Pacing Engine
description: End-to-end machine learning pipeline and interactive web dashboard predicting ultra-endurance pacing across volatile mountain terrain.
img: assets/img/wser_pacer.jpg
importance: 1
category: 
---

## Overview

This project features a production-grade machine learning application designed to predict ultra-endurance pacing at the Western States 100. By feeding physiological profiles and spatial terrain data into a non-linear ensemble model, this engine maps realistic exhaustion curves over 100 miles of volatile trail. The project demonstrates the complete ML lifecycle—from eliminating data leakage in the preprocessing stage to deploying a live, interactive inference dashboard on the cloud.

## Core Pipeline & Data Operations

- **Automated Preprocessing Gateways:** Architected a robust `scikit-learn` pipeline leveraging `ColumnTransformer` and `StandardScaler` to automate the encoding of categorical variables and the scaling of numerical telemetry, strictly eliminating data leakage prior to model training.
- **Dynamic Inference Engine:** Programmed an iterative simulation loop that dynamically updates cumulative fatigue markers (elapsed hours and distance) based on the model's previous segment predictions, reflecting the compounding nature of biological exhaustion.
- **Artifact Serialization:** Packaged the entire preprocessing architecture and trained model into a lightweight `.joblib` deployment artifact, ensuring rapid, stateless inference capabilities in a cloud-hosted environment.

## Statistical Modeling & Insights

- **Non-Linear Ensemble Modeling:** Engineered a Random Forest Regressor to capture the complex, non-linear biological "cliffs" where steep elevation grades and late-stage fatigue force runners into hiking, vastly outperforming baseline linear models.
- **Predictive Performance Metrics:** Evaluated pipeline accuracy using advanced regression metrics, achieving a high R-squared of 0.8249 and reducing the Mean Absolute Error (MAE) to a highly accurate 0.31 mph.
- **Interactive Data Visualization:** Deployed a live `Streamlit` web application that allows users to adjust physiological inputs (age, gender) and instantly generates dynamic turn-by-turn data tables and visual speed decay charts.

## Live Project Links

- **Interactive Dashboard:** [Live Simulation Demo](https://wser-trail-velocity-predictor-mindyj.streamlit.app/)
- **Source Code Architecture:** [GitHub Repository](https://github.com/mindyj125/wser-trail-velocity-predictor)

## Tools & Skills

`Python` · `scikit-learn` · `pandas` · `Random Forest` · `Streamlit` · `Machine Learning Pipelines` · `Data Engineering` · `Git` · `Data Visualization`
