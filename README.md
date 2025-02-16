ChatGPT Task Categorization Research

Overview

This research focuses on categorizing ChatGPT-generated tasks using a combination of machine learning models and clustering techniques. The goal is to analyze and structure various task categories, improving task classification using advanced embedding and clustering methods.

Methodology

We employed the following techniques to categorize ChatGPT-generated tasks:

Embeddings

BAAI/bge-large-en

mistralai/Mistral-7B

Clustering

HDBSCAN: Used for density-based clustering to filter noise.

Spectral Clustering: Applied for refined grouping of tasks.

K-Means & MiniBatch K-Means: Used for final task categorization.

Dimensionality Reduction

t-SNE & UMAP: Applied to visualize high-dimensional embeddings in 2D/3D.

Evaluation Metrics

Silhouette Score: Measures cluster separation.

Calinski-Harabasz Index: Assesses clustering compactness.

Davies-Bouldin Score: Evaluates cluster quality.

Key Results

Achieved a Silhouette Score of 0.5039 using KMeans on DBSCAN-filtered data.

Improved clustering performance using a combination of HDBSCAN + Spectral Clustering.

Generated 2D and 3D UMAP visualizations for better interpretability.

Contributions

Developed a structured taxonomy of ChatGPT task categories.

Enhanced clustering performance with advanced machine learning techniques.

Provided insights into effective task classification methods for AI-generated content.

Future Work

Further optimization of clustering algorithms.

Exploring explainability techniques (e.g., SHAP, LIME) for interpretability.

Expanding dataset coverage for more generalized task categorization.

Authors:  V.Teja sri
          T.Pranathi
          S.Varshitha


