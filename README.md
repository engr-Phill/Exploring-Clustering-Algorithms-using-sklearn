# Clustering Algorithms Exploration Project

## Project Overview

This project is designed to enhance my knowledge of various clustering algorithms, understand their strengths and weaknesses, and become familiar with popular industry tools used for clustering tasks. The goal is to gain hands-on experience with different clustering techniques and evaluate their performance on various datasets.

## Contents

- `Code.ipynb`: The main Jupyter notebook containing the implementation of different clustering algorithms, their evaluation, and comparison.
- [My Analysis of Algorithms](https://github.com/engr-Phill/Exploring-Clustering-Algorithms-using-sklearn/blob/main/Analysis%20of%20Algorithms.pdf)
## Clustering Algorithms Covered

1. **K-Means Clustering**
   - Simple and fast.
   - Works well with spherical clusters.
   - Not suitable for clusters with complex shapes.

2. **Affinity Propagation**
   - Does not require the number of clusters to be specified beforehand.
   - Suitable for non-spherical clusters.
   - Computationally intensive and sensitive to parameters.

3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
   - Can find arbitrarily shaped clusters.
   - Robust to noise and outliers.
   - Requires careful selection of parameters (epsilon and min_samples).

4. **Gaussian Mixture Model (GMM)**
   - Probabilistic model.
   - Can handle clusters of different shapes and sizes.
   - May converge to local minima.

5. **BIRCH (Balanced Iterative Reducing and Clustering using Hierarchies)**
   - Suitable for large datasets.
   - Performs hierarchical clustering.
   - Efficient and scalable.

6. **Agglomerative Clustering**
   - A type of hierarchical clustering.
   - Merges clusters iteratively.
   - Computationally intensive for large datasets.

7. **Mean Shift**
   - Does not require the number of clusters to be specified beforehand.
   - Can find clusters of arbitrary shape.
   - Computationally expensive.

## Tools and Libraries Used

- **Python**: Programming language used for implementing the clustering algorithms.
- **Jupyter Notebook**: Interactive environment for running the code and visualizing the results.
- **Scikit-learn**: Machine learning library providing implementations of various clustering algorithms.
- **Matplotlib/Seaborn**: Libraries for data visualization.

## How to Run the Code

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running:
   ```bash
   pip install -r requirements.txt
