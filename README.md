# Galaxy Classification Project

Created a machine learning project aimed at classifying galaxies into three main types: Spiral, Elliptical, and Uncertain, based on certain features obtained from astronomical observations.

## Overview

The goal of this project is to accurately classify galaxies into one of the three classes mentioned above. The dataset used in this project contains observations collected by the Galaxy Zoo project.

## Project Workflow

1. **Data Collection and Preprocessing**: The dataset, obtained from the Galaxy Zoo project, was preprocessed to remove irrelevant columns, combine classes, and visualize the distribution of various features.

2. **Data Splitting**: The dataset was split into training, validation, and test sets to train and evaluate machine learning models.

3. **Model Building and Evaluation**: Several classification models were trained, including K-Nearest Neighbors, Naive Bayes, and Logistic Regression. Each model was evaluated using performance metrics such as precision, recall, and accuracy.

4. **Results**: The performance of each model is detailed in the project notebooks along with visualizations of the data distribution and model predictions.

## Conclusion

The Galaxy Classification Project aimed to classify galaxies into three main types: Spiral, Elliptical, and Uncertain, utilizing various machine learning models. The analysis and evaluation of these models provided valuable insights into their performance:

- **K-Nearest Neighbors (KNN)**: This model exhibited strong overall accuracy, particularly in classifying Spiral and Uncertain galaxies. With an accuracy of 87%, KNN demonstrated robust predictive capabilities, especially for Spiral galaxies.

- **Naive Bayes**: Naive Bayes showed varying results across classes, achieving a noteworthy 79% accuracy. It excelled in predicting Elliptical galaxies with a high recall of 97% but demonstrated comparatively lower performance for Spirals and Uncertain types.

- **Logistic Regression**: The Logistic Regression model, despite convergence warnings during training, displayed performance similar to Naive Bayes, achieving an accuracy of 79%. It showcased higher recall for Elliptical galaxies but relatively lower precision and recall for Spirals and Uncertain types.

The model evaluations indicate that while KNN emerged as the top-performing model with the highest overall accuracy, Naive Bayes excelled in precision for predicting Elliptical galaxies. Logistic Regression demonstrated competitive results but might require additional parameter tuning or data scaling to optimize its performance.
