# Identifying Steam Game Market Segments Through Pricing, Player Engagement, and Ownership Patterns

Data Mining Lab. Capstone Project  
Made by: De Castro, Rain Jade C.


---

## Problem Statement

In today's PC gaming market, platforms like Steam host tens of thousands of competing games, making it hard for developers to get noticed, attract buyers, and keep players interested [(Wang et al., 2025)](https://pdfs.semanticscholar.org/2215/1c7f09cb66e69613aab62928a3ecedd1811a.pdf). <ins>**Game developers, especially independent and mid-sized teams**, often struggle to understand existing market trends and apply when making key business decisions.</ins> This project aims to identify meaningful groups of games with similar characteristics and analyze the differences between the clusters in terms of pricing, ownership, player engagement, and satisfaction.

## Main Data Mining Question

> "What distinct groups of Steam games can be identified based on their pricing, player engagement, and ownership patterns, and what characteristics distinguish each group?"

## Dataset Description

[Steam Dataset for Recommendation & Prediction](https://www.kaggle.com/datasets/patelris/steam-top-1495-games-dataset/data) is a dataset made by Rishi Patel uploaded on Kaggle. The original dataset contains 1495 games and 29 features. This dataset presents information about the selected Steam games including their game details, pricing, genres, platform availability, estimated ownership, player reviews, and playtime statistics.

## Tools Used

- **Python** — for performing data analysis and clustering
- **Google Colab** — for writing and executing Python code
- **Pandas** — for loading, cleaning, and modifying the dataset
- **NumPy** — for numerical operations and calculations
- **Scikit-learn** — for implementing K-Means clustering, feature scaling

## Data Mining Technique

Clustering, using **K-Means Clustering** algorithm. This algorithm will be used to identify groups of Steam games with similar characteristics in terms of pricing, player engagement, and ownership.

## Expected Output

This project is expected to produce distinct clusters of Steam games based on features like pricing, player engagement, and ownership using K-Means Clustering, presented through a Scatter Plot. Each cluster will represent a characteristic common around the games within the cluster, and create an analysis between different segments of the Steam market.

## Limitations

- The dataset represents a selection of top Steam games and does not reflect the entire Steam catalog.
- Ownership figures are estimates and in ranges rather than exact values.
- Missing values and extreme observations may affect the clustering results in K-Means.
- The clusters observed does not establish causal relationships between game characteristics and commercial success.
