# CS4168-Data-Mining-Project

## Contributors
- Italo da Silva
- Craig Phayer
- Boris Bobylkov
- Symon Szulc
- Martynas Danys

## Project Specification

### Dataset and Predictive Analytics Task
In this project, you must use the dataset provided above. It is an excerpt from the Spotify dataset at https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset.

### Exploratory data analysis: 
Perform exploratory data analysis of the dataset. Comment on your observations.

### Clustering:
Construct and train clustering pipelines for k-means and DBSCAN. When clustering drop the column track_genre. For k-means find the best value of k. Visualise the clusterings and discuss their usefulness for a better understanding of the underlying patterns in the dataset.

### Classification:
Let m be the median of column popularity. Replace column popularity with a binary column popularity_binary with two values: 0 for popularity ≤ m and 1 for popularity > m. Attempt at least three different classification algorithms for training models that can be used for predicting the value of popularity_binary. Construct a pipeline for each of the algorithms you have chosen. Evaluate the trained models and select the best model. Explain your choice in a markdown cell. Aim at training a model that is as good as possible. In this process, you may attempt various data preparation and possibly dimensionality reduction strategies.
