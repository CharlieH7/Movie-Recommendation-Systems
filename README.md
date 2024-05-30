# Movie Recommendation Systems

This repository contains two Jupyter notebooks demonstrating two distinct approaches to building movie recommendation systems: Collaborative Filtering with Singular Value Decomposition (SVD) and Nearest Neighbours with Universal Sentence Encoder (USE). These methodologies are compared to assess their effectiveness in terms of recommendation accuracy, scalability, and user satisfaction.

## Notebooks

### 1. Collaborative Filtering with SVD
This notebook implements a collaborative filtering-based recommendation system using Singular Value Decomposition (SVD). It leverages the MovieLens dataset to predict user ratings for movies and generate personalised movie recommendations. Key steps include:
- Data preprocessing and handling missing values.
- Building the user-item interaction matrix.
- Applying SVD for matrix factorisation.
- Evaluating the model using RMSE and MAE metrics.
- Generating movie recommendations for specific users.

### 2. Nearest Neighbours with USE
This notebook demonstrates a content-based recommendation system using Nearest Neighbours enhanced by the Universal Sentence Encoder (USE). It processes movie titles and genres to generate semantic embeddings and recommend similar movies. Key steps include:
- Data preprocessing and text embedding using USE.
- Building and training the Nearest Neighbours model.
- Evaluating the model using precision, recall, and F1-score metrics.
- Generating movie recommendations based on content similarity.

## Project Structure

- `Collaborative_Filtering_SVD.ipynb`: Notebook for Collaborative Filtering with SVD.
- `Nearest_Neighbours_USE.ipynb`: Notebook for Nearest Neighbours with USE.
- `README.md`: Project description and instructions.

## Requirements

To run these notebooks, you need the following Python packages:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `tensorflow`
- `tensorflow-hub`
- `surprise`

You can install these packages using pip:
```sh
pip install numpy pandas scikit-learn matplotlib tensorflow tensorflow-hub surprise
