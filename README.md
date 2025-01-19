Overview
This project explores how different sampling techniques impact the performance of machine learning models. It shows how various methods for handling data imbalance can affect classification accuracy across different models.

Key Highlights
SMOTE (Synthetic Minority Oversampling Technique) is used to address class imbalance.

Five sampling techniques are compared:

Random Sampling
Stratified Sampling
Systematic Sampling
Cluster Sampling
Bootstrap Sampling
Machine learning models evaluated:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Dataset
The project works with a dataset called sample_dataset.csv, which should follow this structure:

Input Features: Columns representing independent variables.
Target Variable: A column called Class, which is imbalanced.
You can replace sample_dataset.csv with your own dataset as long as it follows this same structure.

Sampling Methods
Here’s how the different sampling methods are used to balance the datasets:

Random Sampling: Randomly picks a subset of the data.
Stratified Sampling: Makes sure the class proportions in the sample match those in the original dataset.
Systematic Sampling: Picks data points at regular intervals (like every 5th record).
Cluster Sampling: Divides the data into clusters and samples from one or more clusters.
Bootstrap Sampling: Selects data with replacement to form a new dataset.
Machine Learning Models
The project tests the following classifiers:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Each model is trained and tested on datasets created using these sampling techniques. The classification accuracy of each model is then compared.
