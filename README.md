# Welcome
<body>
Wecome to my projects page. This is a summary of the machine learning projects I have explored recently.  
<h1>Breast cancer dataset - Classification</h1>
This project is based on the Breast Cancer Wisconsin data, published by UCI Machine learning. It is implemented in Python. The diagnosis (Benign/Malignant) must be predicted from a series of cell measurements (concavity, dimensions, symmetry, ...)

I started by exploring the data, both analytically and visually, before implementing a number of classification algorithms (Logistic regression, Tree classifier, Random Forest, XGBoost, Support Vector Machine and Naive Bayes). The best performer among those base models, a simple classification tree, achieved a recall score of 96.4%  on the test set.(3.6% of the samples labelled as Benign by the classifier are actually malignant).

In a second iteration, I ensembled the 3 best performers with majority vote classifier. This improved model was able to detect all the malignant cases in the sample (recall of 100%). It achieved a global accuracy score of 98%: 7% of the samples labeled as malignant by the model were actually benign.

My detailed analysis can be found here: 
<a href="test.html" title="test.html">Breast cancer Wisconsin - Classification</a>
Tags: Machine Learning | Python | Classification
<body/>
