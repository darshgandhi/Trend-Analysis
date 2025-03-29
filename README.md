# arXiv Data Trend Analysis Project

This repository contains the code and documentation for analyzing the arXiv dataset, focusing on text preprocessing, feature engineering, topic modeling, classification, and visualization.

## Project Overview

This project analyzes arXiv paper abstracts to discover latent topics, classify papers into research domains, and visualize trends in academic research. The project consists of five main components:

1. Data Preprocessing and Exploration
2. Feature Engineering and Representation
3. Topic Modeling and Discovery
4. Classification Model Development
5. Visualization and Insight Generation

## Contributors

- Thoyavan Logan - Data Preprocessing and Exploration
- Darsh Gandhi - Feature Engineering and Representation
- Stany Chabikuli - Topic Modeling and Discovery
- Siddharth Choudhary - Classification Model Development
- Moustapha Yaghi - Visualization and Insight Generation

## Component Details

### Part 1: Data Preprocessing and Exploration

**Responsible for:** Preparing the dataset for analysis

- Load and explore the arXiv dataset (distributions, class balance)
- Clean abstracts (remove special characters, normalize text)
- Perform tokenization, stopword removal, and lemmatization
- Create exploratory visualizations (word frequency, abstract length distribution)
- Generate initial keyword analysis by category

### Part 2: Feature Engineering and Representation

**Responsible for:** Converting text to machine-readable format

- Implement TF-IDF vectorization of abstracts
- Generate BERT embeddings
- Perform dimensionality reduction (PCA, t-SNE, UMAP)
- Compare representation quality between approaches
- Create visualization of paper clusters in reduced space

### Part 3: Topic Modeling and Discovery

**Responsible for:** Uncovering latent topics in the corpus

- Apply LDA topic modeling to discover key topics
- Optimize number of topics using coherence scores
- Extract and interpret top words for each topic
- Map discovered topics to research domains
- Visualize topic distributions across the corpus

### Part 4: Classification Model Development

**Responsible for:** Building predictive models

- Define classification targets (top N topics or research areas)
- Split data into training and testing sets
- Implement multiple classifiers (Naive Bayes, SVM, Neural Networks)
- Optimize hyperparameters for each model
- Evaluate performance using appropriate metrics

### Part 5: Visualization and Insight Generation

**Responsible for:** Creating meaningful visualizations and extracting insights

- Develop interactive topic distribution visualizations
- Create temporal trend analysis of topic popularity
- Identify emerging research areas and declining topics
- Design visualizations showing topic relationships
- Generate research recommendations based on topic analysis
