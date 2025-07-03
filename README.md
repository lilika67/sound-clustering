# Sound Data Clustering Analysis

## Overview

This project conducts an in-depth unsupervised clustering analysis on an unlabeled dataset of 3000 sound recordings, leveraging Mel Spectrogram features to uncover natural groupings. It employs dimensionality reduction techniques (PCA and t-SNE) for visualization and evaluates clustering performance using K-Means and DBSCAN. Key metrics such as a Silhouette Score of 0.8660 and a Davies-Bouldin Index of 0.5379 demonstrate high-quality clusters, making this project valuable for audio classification and pattern recognition tasks.

## Features

- Extracts Mel Spectrogram features (128 bands) from `.wav` or `.mp3` audio files.
- Applies PCA and t-SNE for effective 3D visualization of high-dimensional data.
- Implements K-Means with the elbow method and silhouette scoring for optimal cluster selection.
- Utilizes DBSCAN for density-based clustering with customizable parameters.
- Provides detailed performance metrics (Silhouette Score, Davies-Bouldin Index) and interactive visualizations.
- Includes robust data preprocessing (padding, normalization) to handle variable-length features.

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Required libraries: `numpy`, `pandas`, `librosa`, `matplotlib`, `seaborn`, `scikit-learn`, `zipfile`
- Install dependencies using:
  ```bash
  pip install numpy pandas librosa matplotlib seaborn scikit-learn zipfile

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/lilika67/sound-clustering.git
   cd sound-clustering
   
2.Place the dataset file (unlabelled_sounds.zip) in the project root directory.
3.Install the required dependencies using the command provided in the Prerequisites section.
   
## Project Structure

- `Clustering_assignment_Liliane_Kayitesi .ipynb`: Core Jupyter notebook with code, visualizations, and markdown analysis.
- `Data  - unlabelled_sounds.zip`: Dataset of 3000 sound recordings.
- `README.md`:  documentation file.

## Results

- **K-Means Performance**: Achieved a Silhouette Score of 0.8660 and Davies-Bouldin Index of 0.5379, indicating well-defined, separated clusters.
- **DBSCAN Outcome**: Produced 0 clusters, suggesting the data’s sparsity exceeds DBSCAN’s density threshold.
- **Dimensionality Reduction**: t-SNE visualizations outperformed PCA by preserving non-linear structures, enhancing cluster interpretability.

## Related visualizations 

1. Initial Visualization (Without Dimensionality Reduction)

   ![image](https://github.com/user-attachments/assets/a68ace9d-d97f-423d-9ce7-530be44377bd)

2.PCA nad T-SNE 3D Visualization

![image](https://github.com/user-attachments/assets/ce60bbe1-cf71-49df-98ca-c766ae921d3d)

3. Final visualization using t-SNE

   ![image](https://github.com/user-attachments/assets/58cf8ef3-ea21-41f2-9226-b132a41469fb)



  
  
