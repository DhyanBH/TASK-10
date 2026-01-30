# Task 10: KNN - Handwritten Digit Classification

## 📄 Overview
[cite_start]This project is part of the **AI & ML Internship**[cite: 2]. The goal of this task is to implement the K-Nearest Neighbors (KNN) algorithm to classify handwritten digits. [cite_start]The project involves loading the dataset, preprocessing the data, tuning the hyperparameter $K$, and evaluating the model's performance using accuracy metrics and confusion matrices[cite: 4, 18, 21].

## 📊 Dataset
* [cite_start]**Source:** Scikit-learn `load_digits()` dataset[cite: 6].
* **Description:** The dataset consists of 8x8 pixel images of handwritten digits (0-9).

## 🛠️ Tools & Technologies Used
* [cite_start]**Python** [cite: 9]
* [cite_start]**Scikit-learn** (for model building, datasets, and metrics) [cite: 10]
* [cite_start]**Matplotlib** (for data visualization and plotting) [cite: 11]
* **NumPy** (for numerical operations)

## 🚀 Steps Implemented
1.  [cite_start]**Data Loading:** Loaded the digits dataset and visualized sample images to understand the structure[cite: 14, 15].
2.  **Preprocessing:**
    * [cite_start]Split the data into training and testing sets (80-20 split)[cite: 16].
    * [cite_start]Applied **StandardScaler** to normalize the features, as KNN is distance-based and sensitive to feature magnitudes[cite: 17].
3.  [cite_start]**Model Training:** Trained a KNN classifier initially with $K=3$[cite: 18].
4.  [cite_start]**Hyperparameter Tuning:** Tested multiple values of $K$ (3, 5, 7, 9) to find the optimal number of neighbors[cite: 19].
5.  **Evaluation:**
    * [cite_start]Plotted **Accuracy vs. K** to visualize the best hyperparameter[cite: 20].
    * [cite_start]Generated a **Confusion Matrix** to analyze misclassified digits[cite: 21].
    * [cite_start]Displayed test images with their predicted labels[cite: 22].

## 📈 Results & Visualizations

### Accuracy vs. K Value
*The graph below shows how the model accuracy changes with different values of K.*

![Accuracy Plot](path_to_your_accuracy_plot_image.png)
*(Note: Replace the text above with your actual image path or screenshot after uploading it to the repo)*

### Confusion Matrix
*The confusion matrix helps identify which digits the model confuses with others.*

![Confusion Matrix](path_to_your_confusion_matrix_image.png)
*(Note: Replace the text above with your actual image path or screenshot)*

## 🧠 Key Learnings
Through this task, I explored:
* [cite_start]**Distance-based Classification:** Understanding Euclidean distance[cite: 32].
* [cite_start]**Hyperparameter Tuning:** How choosing the right $K$ impacts model performance (Underfitting vs. Overfitting)[cite: 30, 33].
* [cite_start]**Feature Scaling:** Why standardization is critical for algorithms like KNN[cite: 31].

## 💻 How to Run
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install numpy pandas scikit-learn matplotlib
    ```
3.  Run the Jupyter Notebook or Python script.

---
[cite_start]*Task completed for Elevate Labs AI & ML Internship.* [cite: 1]
