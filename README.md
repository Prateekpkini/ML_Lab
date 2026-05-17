# Machine Learning Lab Repository

This repository contains a collection of Python scripts demonstrating various fundamental machine learning algorithms, data preprocessing, and visualization techniques. The implementations primarily use `scikit-learn`, `pandas`, `numpy`, `matplotlib`, and `seaborn`.

## Repository Contents

Below is a breakdown of the programs included in this repository:

### 1. Exploratory Data Analysis (EDA) (`p1.txt`)
* **Description:** Performs basic EDA on the `ibm_hr_employee-attrition.csv` dataset. 
* **Key Features:** Calculates statistics (mean, median, mode, variance, standard deviation) for numerical columns. Identifies outliers using the Interquartile Range (IQR). Generates histograms, boxplots, bar charts, and pie charts for data visualization.

### 2. Correlation and Covariance (`p2.txt`)
* **Description:** Computes the Pearson correlation coefficient and covariance matrix for the `iris` dataset.
* **Key Features:** Visualizes the relationship between features using a scatter plot and a heatmap of the correlation matrix.

### 3. Principal Component Analysis (PCA) (`p3.txt`)
* **Description:** Applies dimensionality reduction using PCA on the `iris` dataset.
* **Key Features:** Standardizes the data and reduces it to two principal components (PC1 and PC2). Plots the resulting 2D projections color-coded by the target species.

### 4. k-Nearest Neighbors (k-NN) Classification (`p4.txt`)
* **Description:** Implements regular and distance-weighted k-NN classifiers on the `iris` dataset.
* **Key Features:** Tests the model for varying values of $k$ ($k=1, 3, 5$). Evaluates and compares performance using Accuracy and weighted F1-score.

### 5. Locally Weighted Regression (LWR) (`p5.txt`)
* **Description:** Implements the non-parametric Locally Weighted Regression algorithm from scratch.
* **Key Features:** Generates a synthetic non-linear dataset. Fits the LWR curve to the dataset using a bandwidth/tau parameter and calculates the Mean Squared Error (MSE).

### 6. Decision Tree Classification (`p7.txt`)
* **Description:** Builds a Decision Tree Classifier to predict passenger survival using the `titanic` dataset.
* **Key Features:** Handles categorical mapping for features like 'sex' and 'embarked'. Evaluates the model using Accuracy, Precision, Recall, and F1 Score, and visualizes the tree structure.

### 7. Naive Bayes Classification (`p8.txt`)
* **Description:** Implements a Gaussian Naive Bayes classifier on the `iris` dataset.
* **Key Features:** Evaluates model predictions using accuracy scores and a detailed classification report. Visualizes the classification results using a confusion matrix heatmap.

### 8. K-Means Clustering (`p9.txt`)
* **Description:** Applies K-Means clustering ($k=2$) to the Wisconsin Breast Cancer dataset.
* **Key Features:** Standardizes the data before clustering. Evaluates the clustering using the Silhouette Score and Adjusted Rand Index. Uses PCA to reduce dimensions for 2D visualization and compares the generated clusters with the true labels side-by-side.

## Prerequisites

To run the scripts in this repository, you need Python installed along with the following libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
