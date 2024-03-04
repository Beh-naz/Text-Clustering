# Text-Clustering
This project demonstrates text clustering using the unsupervised machine learning algorithm KMeans on a dataset of BBC news articles. The goal is to cluster the articles into different categories based on their content.

## dataset
The dataset is the BBCNewsDataset.xlsx which has been uploaded to this repository.

## Environment Setup
Required packages to install: openpyxl, wordcloud, matplotlib, scikit-learn, nltk.

## Helper Functions
preprocess_text: Preprocesses the text data for clustering.

generate_subplot_index: Generates subplot indices for visualization.

plot_clusters, plot_clusters_silhouette_scores, plot_clusters_wcss_scores, plot_wordcloud: Plotting functions for cluster visualization.

report_cluster_external_validation: Reports external validation results for the clusters.

## Data Exploration
The dataset is loaded into a Pandas DataFrame, and basic information about the data is displayed.

## Data Preparation
Text data is preprocessed using NLTK for tokenization, lemmatization, stop word removal, and punctuation, numbers, and special characters removal.

## KMeans Model Development
A KMeans model is trained with different numbers of clusters, and cluster quality metrics like silhouette score and WCSS are calculated.

## Optimal Model Selection & Clusters Visualization
The optimal number of clusters is selected based on the silhouette score, and clusters are visualized using PCA and word clouds.

## External Validation
The clusters are externally validated using the news label field to assess the quality of the clustering.

