Project Overview
This project implements a K-Nearest Neighbors (KNN) algorithm to classify handwritten digits (0-9) using the Scikit-learn load_digits() dataset. The goal is to explore how different K values (neighbors) and feature scaling affect the accuracy of a distance-based classifier.  
Dataset
Source: sklearn.datasets.load_digits().  
Structure: 1,797 samples of 8x8 grayscale images.  
Task: Multi-class classification of digits 0 through 9.
Implementation Steps
Data Exploration: Visualized the dataset to confirm image-to-label alignment.  
Preprocessing: Applied StandardScaler to the features because KNN uses distance metrics (Euclidean) and is sensitive to the scale of input data.  
Model Training: Initialized the model with K=3.  
Hyperparameter Tuning: Tested K values of 3, 5, 7, and 9 to find the optimal neighbor count.  
Evaluation: Generated an Accuracy vs K plot and a Confusion Matrix to identify specific misclassifications.  
Results
Best K Value: [Insert your best K here, e.g., 3]
Test Accuracy: [Insert your percentage here, e.g., 98.5%]
Key Finding: Scaling significantly improved accuracy compared to unscaled data because pixel intensity values were normalized.
