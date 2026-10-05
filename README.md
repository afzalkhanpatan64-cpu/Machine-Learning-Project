Iris Flower Classification Project

An end-to-end machine learning project demonstrating exploratory data analysis (EDA), algorithm spot-checking, and model evaluation using the classic Iris dataset.

🌸 Project Overview

The goal of this project is to build a robust multi-class classification model that can predict the species of an iris flower based on four specific physical measurements (sepal length, sepal width, petal length, and petal width).

📊 Dataset Features

The dataset contains 150 samples evenly distributed across three species (50 samples each):

1. Iris-setosa

2. Iris-versicolor

3. Iris-virginica

Features:

--sepal-length (cm)

--sepal-width (cm)

--petal-length (cm)

--petal-width (cm)

🛠️ Tech Stack & Libraries

Python 3.x

--Pandas (Data loading and manipulation)

--Matplotlib (Data visualization & plotting)

--Scikit-Learn (Machine learning modeling, cross-validation, and metrics)

🚀 Workflow & Methodology
1. Data Loading & Inspection: Loaded the Iris dataset, checked data dimensions ($150 \times 5$), reviewed the first 20 rows, and calculated summary statistics.
2. Exploratory Data Analysis (EDA):
   Checked class balance across target categories.
   Generated box-and-whisker plots to identify feature ranges and outliers.
   Plotted histograms to understand feature distributions.
   Visualized feature interactions using a scatter plot matrix.
   
3. Data Splitting: Split the dataset into training and validation sets using an 80/20 train-test split (test_size=0.20, random_state=7).

4. Algorithm Spot-Checking: Evaluated 6 diverse classification algorithms using 10-fold cross-validation with accuracy scoring:

   Logistic Regression (LR)

   Linear Discriminant Analysis (LDA)

   K-Nearest Neighbors (KNN)

   Classification and Regression Trees (CART / Decision Tree)

   Gaussian Naive Bayes (NB)

   Support Vector Machine (SVM)

5. Model Evaluation: Trained the K-Nearest Neighbors (KNN) classifier on the training split, evaluated it on the validation set, and generated a confusion matrix     and classification report.

📈 Results & Performance

The K-Nearest Neighbors (KNN) model achieved an overall accuracy of 90% on the validation dataset.

--Classification Report Highlights:

   -Iris-setosa: Precision: 1.00 | Recall: 1.00 | F1-Score: 1.00

   -Iris-versicolor: Precision: 0.85 | Recall: 0.92 | F1-Score: 0.88

   -Iris-virginica: Precision: 0.90 | Recall: 0.82 | F1-Score: 0.86

⚙️ How to Run

1. Ensure you have Python and the required libraries installed:

   pip install pandas matplotlib scikit-learn


2. Place the iris.csv file in your working directory.

3. Run the Jupyter Notebook (Machine_Learning_Project.ipynb) or execute the Python cells sequentially.

