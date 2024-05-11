<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breast Cancer Classification - README</title>
</head>
<body>
    <h1>Breast Cancer Classification</h1>

    <h2>Project Description:</h2>
    <p>This project aims to classify breast cancer tumors as malignant or benign using machine learning algorithms. The dataset utilized is the Breast Cancer Wisconsin (Diagnostic) dataset, which contains features computed from digitized images of fine needle aspirates (FNAs) of breast masses. These features describe characteristics of cell nuclei present in the images.</p>

    <h2>Dataset Information:</h2>
    <ul>
        <li>Number of Instances: 569</li>
        <li>Number of Attributes: 30 numeric predictive attributes and the class</li>
        <li>
            <h3>Attribute Information:</h3>
            <ul>
                <li>Features include radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension, each with mean, standard error, and worst/largest values.</li>
                <li>Class: Malignant or Benign</li>
            </ul>
        </li>
        <li>
            <h3>Summary Statistics:</h3>
            <p>Provides minimum and maximum values for each attribute.</p>
        </li>
        <li>
            <h3>Class Distribution:</h3>
            <p>Malignant: 212, Benign: 357</p>
        </li>
        <li>Creators: Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian</li>
        <li>Date: November, 1995</li>
        <li>Source: <a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)">UCI Machine Learning Repository</a></li>
    </ul>

    <h2>Preprocessing:</h2>
    <ul>
        <li>Split the dataset into training and testing sets.</li>
        <li>Scale the features using MinMaxScaler to normalize them between 0 and 1.</li>
    </ul>

    <h2>Classification Models:</h2>
    <ol>
        <li>
            <h3>Naive Bayes (GaussianNB):</h3>
            <ul>
                <li>Fit a Gaussian Naive Bayes classifier.</li>
                <li>Calculate accuracy, precision, and recall.</li>
            </ul>
        </li>
        <li>
            <h3>K-Nearest Neighbors (KNN):</h3>
            <ul>
                <li>Fit a K-Nearest Neighbors classifier with specified parameters.</li>
                <li>Evaluate performance metrics.</li>
            </ul>
        </li>
        <li>
            <h3>Decision Tree:</h3>
            <ul>
                <li>Train a Decision Tree classifier with set parameters.</li>
                <li>Measure accuracy, precision, and recall.</li>
            </ul>
        </li>
        <li>
            <h3>Random Forest:</h3>
            <ul>
                <li>Utilize a Random Forest classifier with defined hyperparameters.</li>
                <li>Assess performance metrics.</li>
            </ul>
        </li>
        <li>
            <h3>Support Vector Machine (SVM):</h3>
            <ul>
                <li>Train a Support Vector Machine classifier with a polynomial kernel.</li>
                <li>Evaluate accuracy, precision, and recall.</li>
            </ul>
        </li>
        <li>
            <h3>Logistic Regression:</h3>
            <ul>
                <li>Fit a Logistic Regression classifier.</li>
                <li>Calculate performance metrics.</li>
            </ul>
        </li>
        <li>
            <h3>Artificial Neural Network (ANN):</h3>
            <ul>
                <li>Train a Multi-Layer Perceptron classifier with specified architecture.</li>
                <li>Evaluate accuracy, precision, and recall.</li>
            </ul>
        </li>
    </ol>

    <h2>Model Comparison:</h2>
    <ul>
        <li>Visualize the accuracy scores of different models using bar plots.</li>
        <li>Evaluate performance metrics for each model.</li>
    </ul>

    <h2>Code Integration:</h2>
    <p>Below is the Python code integrated with the HTML README:</p>

    <pre><code>
        // Python code goes here
    </code></pre>
</body>
</html>
