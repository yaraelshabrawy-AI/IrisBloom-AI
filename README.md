# IrisBloom-AI
IrisBloom AI – Flower Species Classification

Project Overview

IrisBloom AI is a Machine Learning project that classifies Iris flowers into different species based on their physical measurements.

The project uses the Iris dataset and applies data preprocessing, data visualization, and Machine Learning algorithms to predict the flower species.

Project Objectives

* Explore and understand the Iris dataset.
* Clean and preprocess the data.
* Visualize important features and patterns.
* Train Machine Learning classification models.
* Compare model performance using accuracy.
* Predict the species of a new Iris flower.

Dataset

The project uses the Iris Dataset, which contains measurements of three Iris flower species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

Features:

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)
* Sepal Area (Engineered Feature)

Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

Project Workflow

1. Data Preprocessing

* Load the dataset.
* Explore the data using head(), info(), and describe().
* Remove duplicate records.
* Handle missing values.
* Drop unnecessary columns.
* Encode categorical target labels.

2. Feature Engineering

* Create a new feature called Sepal_Area by multiplying Sepal Length by Sepal Width.

3. Data Visualization

* Histogram to visualize Sepal Length distribution.
* Scatter plot to explore the relationship between Petal Length and Petal Width.
* Count plot to visualize the distribution of flower species.

4. Model Training

Two Machine Learning classification algorithms are implemented:

* Decision Tree Classifier
* K-Nearest Neighbors (KNN)

The dataset is split into:

* 80% Training Data
* 20% Testing Data

5. Model Evaluation

* Evaluate both models using Accuracy Score.
* Compare their performance.
* Identify which model achieved higher accuracy.

6. Prediction

Use the trained Decision Tree model to predict the species of a new Iris flower based on its measurements.

Machine Learning Models

Model	Algorithm
Model 1	Decision Tree
Model 2	K-Nearest Neighbors (KNN)

Limitations

* The dataset is relatively small.
* Model accuracy may vary depending on the data split.
* KNN may benefit from feature scaling.
* Predictions are not guaranteed to be 100% accurate.

 Future Improvements

* Apply feature scaling to improve KNN performance.
* Experiment with additional classification algorithms.
* Perform hyperparameter tuning.
* Use cross-validation for more reliable evaluation.
* Build a simple web application for flower species prediction.

Author

Yara Elshabrawy 

Project Type

Machine Learning – Classification



This project was developed as a practical introduction to Data Analysis and Machine Learning using Python and Scikit-learn.
