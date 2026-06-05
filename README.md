# Student Success Prediction and Clustering Analysis

## Project Overview

This project aims to analyze student performance data from an online learning platform to better understand student behavior and predict academic success.

The project consists of two main parts:

### Part 1: Student Clustering

The objective of this section is to segment students into meaningful groups based on their demographic characteristics, educational background, and assessment performance.

The clustering process includes:

* Data exploration and preprocessing.
* Feature scaling using StandardScaler.
* Determining the optimal number of clusters using the Elbow Method and Silhouette Score.
* Applying K-Means clustering.
* Visualizing clusters using Principal Component Analysis (PCA).
* Analyzing cluster characteristics and identifying key differences between student groups.

The clustering analysis revealed two distinct student groups. One cluster generally demonstrated stronger academic performance and higher course completion rates, while the other cluster showed lower assessment scores and a lower probability of passing the course.

---

### Part 2: Student Success Prediction

The objective of this section is to build a predictive model capable of identifying whether a student will pass or fail a course.

The modeling workflow includes:

* Data preprocessing and cleaning.
* Splitting the dataset into training and testing sets using a fixed random state.
* Dimensionality reduction using Principal Component Analysis (PCA).
* Building and evaluating multiple Deep Learning models using TensorFlow/Keras.
* Comparing model performance using Accuracy, Precision, Recall, and F1-Score.
* Selecting the best-performing model for deployment.

Three neural network models were developed and compared. Model 2 achieved the best overall performance and was selected as the final model based on its superior Accuracy, Recall, and F1-Score.

---

## Business Value

The developed solution can help educational institutions:

* Identify students at risk of academic failure.
* Provide early interventions and personalized support.
* Improve student retention and completion rates.
* Support data-driven educational decision-making.
* Enhance overall student success outcomes.

This project demonstrates how clustering techniques and deep learning models can be combined to generate actionable insights and predictive solutions in educational analytics.
