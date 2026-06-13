---
layout: page
title: Communicative Efficiency of Non-compositional Language
description: NLP and data processing pipeline analyzing processing ease, semantic transparency, and frequency metrics across large-scale English and Mandarin text corpora
img: assets/img/nlp_linguistics.jpg
importance: 2
category:
---

## Overview

Conducted at the UC Berkeley Department of Linguistics, this project investigates the communicative efficiency of non-compositional language (idioms and figurative expressions) across English and Mandarin Chinese text corpora. By building comprehensive NLP data pipelines, this research extracts semantic metrics—such as word frequency distributions and concreteness norms—to evaluate how idiomatic phrasing balances processing ease against informativity across over 5,000 idiom instances.

## Core Pipeline & Data Operations

- **Text Corpus Preprocessing:** Built and optimized Python NLP pipelines leveraging `spaCy` and `NLTK` to lemmatize tokens, strip punctuation, isolate stop words, and handle data normalization (such as traditional vs. simplified Chinese characters).
- **Heuristic Alignment & Extraction:** Implemented string-distance and context-window heuristic algorithms to programmatically align idiomatic expressions with their literal translation segments across multi-source datasets.
- **Multi-Set Character Analytics:** Developed a character-bag subtraction system using Python's `Counter` multi-sets to programmatically isolate shared syntactic structures from unique, idiom-specific semantic components.
- **Data Integrity & Error Masking:** Engineered rigorous data-cleaning workflows with comprehensive error-code logging to flag and exclude malformed datasets, missing metrics, or severe translation alignment issues.

## Statistical Modeling & Insights

- **Linguistic Metrics Calculation:** Calculated log-transformed frequency statistics (averages, maximums, minimums, and totals) alongside Brysbaert concreteness mappings to evaluate systemic text density.
- **Statistical Testing:** Applied hypothesis testing ($t$-tests) and Pearson correlation analysis to analyze the relationships between semantic transparency, contextual usage, and baseline cognitive processing friction.
- **Data Visualization:** Deployed `Matplotlib` and `Seaborn` to generate distributional data visualizations of semantic transparency, communicating findings on figurative language efficiency directly to department leadership.

## Tools & Skills

`Python` · `pandas` · `NumPy` · `spaCy` · `NLTK` · `Regex` · `NLP` · `Statistical Modeling` · `Data Pipelines` · `Matplotlib` · `Seaborn` · `Corpus Linguistics`
