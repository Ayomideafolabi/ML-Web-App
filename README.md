# ML-Web-App

## Machine Learning Classifier App

This project is an interactive machine learning web application developed using **Streamlit** and **Scikit-learn**. The application allows users to explore and compare different classification algorithms on several built-in machine learning datasets.

### Features

The application allows users to:

* Select one of three datasets: **Iris, Breast Cancer, or Wine**.
* Select one of three classification algorithms: **K-Nearest Neighbors (KNN), Support Vector Machine (SVM), or Random Forest**.
* Adjust classifier hyperparameters using interactive sidebar sliders.
* Automatically split the selected dataset into **80% training data and 20% testing data**.
* Train the selected classifier on the training dataset.
* Make predictions on the testing dataset.
* Evaluate model performance using **classification accuracy**.
* Display a **confusion matrix** to show how the classifier performed across the different classes.
* Use **Principal Component Analysis (PCA)** to reduce the dataset to two dimensions for visualization.
* Display a scatter plot of the PCA-transformed data, with colors representing the different target classes.

### Application Workflow

The overall workflow of the application is:

**Select Dataset → Select Classifier → Adjust Hyperparameters → Split Data → Train Model → Make Predictions → Evaluate Performance → Visualize Data**

The purpose of the application is to provide a simple interactive environment for exploring how different machine learning classifiers and hyperparameter settings perform on different datasets.
