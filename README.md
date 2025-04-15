# CS4168-Data-Mining-Project

## Contributors
- Italo da Silva
- Craig Phayer
- Boris Bobylkov
- Symon Szulc
- Martynas Danys

## Project Specification

1. Dataset: tracks.csv

2. Project Teams
   This is a group project. Each group must consist of 3-5 students, and typically 4 students.

3. Tasks

- 3.1 Dataset and Predictive Analytics Task
  In this project, you must use the dataset provided above. It is an excerpt from the [Spotify dataset](https://huggingface.co/datasets/maharshipandya/spotify-tracks-dataset).

- 3.2 Use the lab exercises as the basis for creating one or multiple Jupyter notebooks that contain:


    - a. The names and IDs of the students in your project group, which parts of the project each student has worked on,
        and what percentage of the whole work on the project is their contribution. If you submit multiple notebooks, include this information in all notebooks.
        If the percentage of work done by each student is not specified, it will be assumed that all team members contributed equally to the project.
  

    - b. Exploratory data analysis: Perform exploratory data analysis of the dataset. Comment on your observations.


    - c. Clustering: Construct and train clustering pipelines for k-means and DBSCAN. When clustering drop the column track_genre.
        For k-means find the best value of k. Visualise the clusterings and discuss their usefulness for a better understanding of the underlying patterns in the dataset.


    - d. Classification: Let m be the median of column popularity. Replace column popularity with a binary column popularity_binary with two values:
        0 for popularity ≤ m and 1 for popularity > m. Attempt at least three different classification algorithms for training models that can be used for predicting the value of popularity_binary.
        Construct a pipeline for each of the algorithms you have chosen. Evaluate the trained models and select the best model.
        Explain your choice in a markdown cell. Aim at training a model that is as good as possible.
        In this process, you may attempt various data preparation and possibly dimensionality reduction strategies.


4. Submission
   Deadline: Sunday, 27th of April, 23:55
   Submit your Jupyter Notebooks on Brightspace.

## Rubric

### 3.2b EDA – *8 marks*
For higher marks: Aim at utilising various plotting techniques. Comment on the insights provided by each plot. Draw overall conclusions from the EDA.

---

### 3.2c Clustering – *9 marks*
For higher marks: Fine-tune some of the parameters of the estimators in the pipeline with grid search. Attempt to describe the clusters you have found with words.

---

### 3.2d Classification – *8 marks*
For higher marks: Fine-tune some of the parameters of the estimators in the pipeline with grid search.