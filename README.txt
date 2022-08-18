Academic Course Project
Course name: Pattern Recognition
Project name: Wine Quality Prediction

Group members:
-> Kamarthi Litheesh Kumar
-> Kamalapuram Sreenivasulu Reddy
-> Kakarla Venkata Sesha Sai Pavanteja

Implementation:
1. Removed fixed acidity, volatile acidity, citric acid, residual sugar, free sulphur dioxide, total sulphur dioxide, sulphates features because they are less correlated with quality of wine.
2. Combined both white wine and red wine datasets
    • White wine -1
    • Red wine - 0
3. Normalized the features so that equal distribution of variance will be there for all features
4. Trained these features to Logistic Regression, Gaussian SVM, Neural Network Classifiers and obtained confusion matrices, accuracy, ROC Curves
5. Tested the data using above trained models, result is the test accuracy
    • Principal Component Analysis, or PCA, is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.
    • Because smaller data sets are easier to explore and visualize and make analysing data much easier and faster
    • PCA is keeping enough components to explain 95% variance. After training, 4 components were kept.
    • Explained variance per component (in order): 47.5%, 26.0%, 18.6%, 7.9%
