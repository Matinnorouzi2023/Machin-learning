<h1>Breast Cancer Classification</h1>

<h2>Project Description:</h2>
<p>This project aims to classify breast cancer tumors as malignant or benign using machine learning algorithms. The dataset utilized is the Breast Cancer Wisconsin (Diagnostic) dataset.</p>

<h2>Dataset Information:</h2>
<ul>
  <li><strong>Number of Instances:</strong> 569</li>
  <li><strong>Number of Attributes:</strong> 30 numeric predictive attributes and the class</li>
  <li><strong>Summary Statistics:</strong> Provides minimum and maximum values for each attribute.</li>
  <li><strong>Class Distribution:</strong> Malignant: 212, Benign: 357</li>
  <li><strong>Creators:</strong> Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian</li>
</ul>

<h2>Preprocessing:</h2>
<p>Split the dataset into training and testing sets. Scale the features using MinMaxScaler to normalize them between 0 and 1.</p>

<h2>Classification Models:</h2>
<ol>
  <li><strong>Naive Bayes (GaussianNB)</strong></li>
  <li><strong>K-Nearest Neighbors (KNN)</strong></li>
  <li><strong>Decision Tree</strong></li>
  <li><strong>Random Forest</strong></li>
  <li><strong>Support Vector Machine (SVM)</strong></li>
  <li><strong>Logistic Regression</strong></li>
  <li><strong>Artificial Neural Network (ANN)</strong></li>
</ol>

<h2>Model Comparison:</h2>
<p>Visualize the accuracy scores of different models using bar plots. Evaluate performance metrics for each model.</p>








<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breast Cancer Classification</title>
    <!-- Add any necessary CSS stylesheets or external libraries here -->
</head>
<body>
    <h1>Breast Cancer Classification</h1>
    <p>This project aims to classify breast cancer tumors as malignant or benign using machine learning algorithms.</p>
    
    <h2>Dataset Information</h2>
    <ul>
        <li>Number of Instances: 569</li>
        <li>Number of Attributes: 30 numeric predictive attributes and the class</li>
        <li>Features include radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension</li>
        <li>Class: Malignant or Benign</li>
    </ul>
    
    <h2>Preprocessing</h2>
    <ul>
        <li>Split the dataset into training and testing sets</li>
        <li>Scale the features using MinMaxScaler to normalize them between 0 and 1</li>
    </ul>
    
    <h2>Classification Models</h2>
    <ul>
        <li>Naive Bayes (GaussianNB): Fit a Gaussian Naive Bayes classifier and calculate accuracy, precision, and recall</li>
        <li>K-Nearest Neighbors (KNN): Fit a K-Nearest Neighbors classifier with specified parameters and evaluate performance metrics</li>
        <li>Decision Tree: Train a Decision Tree classifier with set parameters and measure accuracy, precision, and recall</li>
        <li>Random Forest: Utilize a Random Forest classifier with defined hyperparameters and assess performance metrics</li>
        <li>Support Vector Machine (SVM): Train an SVM classifier with a polynomial kernel and evaluate accuracy, precision, and recall</li>
        <li>Logistic Regression: Fit a Logistic Regression classifier and calculate performance metrics</li>
        <li>Artificial Neural Network (ANN): Train an MLP classifier with specified architecture and evaluate accuracy, precision, and recall</li>
    </ul>
    
    <h2>Model Comparison</h2>
    <p>Visualize the accuracy scores of different models using bar plots and evaluate performance metrics for each model.</p>
    
    <!-- Add any additional content or visualizations as needed -->
</body>
</html>

