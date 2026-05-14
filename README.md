# Penguin Clustering

Unsupervised machine learning project using clustering to group penguins based on numerical biological measurements.

## Project Overview

This project applies clustering techniques to a penguin dataset to identify groups of penguins with similar measurement patterns.

The final output summarizes the average numeric characteristics of each cluster in a DataFrame named `stat_penguins`.

## Project Goals

- Load and inspect the penguin dataset
- Clean the dataset by handling missing values
- Select appropriate numeric features for clustering
- Apply a clustering model
- Add cluster labels to the dataset
- Create summary statistics for each cluster

## Required Output

The project requires a DataFrame named `stat_penguins`.

`stat_penguins` should:

- Contain one row per cluster
- Show the mean of the original numeric variables by cluster
- Exclude all non-numeric columns

## Technologies Used

- Python
- pandas
- scikit-learn
- KMeans clustering

## Machine Learning Type

This is an unsupervised learning project.

Unlike regression or classification, clustering does not use a target variable. Instead, the model finds natural groupings in the data based on feature similarity.

## Example Workflow

1. Read the dataset
2. Clean missing values
3. Select numeric columns
4. Fit a clustering model
5. Add cluster labels
6. Group by cluster and calculate mean numeric values

## Repository Structure

penguin-clustering/
│
├── penguin_clustering.ipynb
├── README.md
└── project_requirements.txt

## Dataset Notice

The original dataset may come from an educational platform or course environment and may not be included in this repository.

## Author

Lydia L
