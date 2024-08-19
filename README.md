# SocialMediaSentimentClustering

This repository contains a Jupyter Notebook focused on clustering social media posts based on sentiment analysis on peoples opinions about climate changes. The notebook guides the reader through preprocessing text data, feature extraction, clustering, and visualization, providing insights into distinct sentiment patterns within the dataset.

## Project Overview

### Sentiment Analysis & Clustering

**Objective:**  
The aim of this notebook is to analyze and cluster social media posts according to their sentiment, helping to identify distinct sentiment patterns.

**Key Steps:**
1. **Data Preprocessing**: Loaded and cleaned the text data, handling missing values and removing irrelevant content.
2. **TF-IDF Vectorization**: Transformed the text data into numerical form using TF-IDF vectorization.
3. **Dimensionality Reduction**: Applied Principal Component Analysis (PCA) to reduce the dimensionality of the TF-IDF matrix.
4. **Clustering**: Performed K-Means clustering to group the posts into clusters based on their sentiment.
5. **Visualization**: Created visualizations, including PCA plots, to illustrate the clusters.

**Results:**
- Identified three distinct sentiment clusters within the dataset, each represented by a unique grouping in the PCA plot.
- The results allow for better understanding of the distribution and nature of sentiments in the dataset.
