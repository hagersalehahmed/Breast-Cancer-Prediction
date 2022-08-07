# Predicting  Breast Cancer Based on  Optimized Deep Learning Approach



## Dataset
 We used Breast Cancer Wisconsin (Diagnostic) Dataset (BCWD) to train and evaluate the models. The dataset includes 30 features and one class label. These features describe the cell nuclei detected in the breast picture clip. The class label has two possible values: 0 or 1. Breast cancer can be classified as benign or malignant, with 0 indicating benign and 1 indicating malignant. 
 
## Splitting dataset
The BCWD dataset is divided into two parts: a training set and a testing set. We employed stratified CV to train and optimize the models with the training set, and the results of CV were recorded for each model. Models are evaluated using a testing set, and the results of the testing set were recorded for each model. 

## Machine Learning

 - Five regular machine learning ML models, namely Decision Tree (DT), 
   K-nearest Neighbors (KNN), and Random Forest (RF), Naive Bayes (NB)
   were used. 
 - Grid search with cross-validation is used to optimize ML
   algorithms and improve ML algorithms performance.

## Deep Learning

The optimized deep RNN consists of the input layer, five hidden layers, five dropout layers, and the output layer. In each hidden layer, we optimized the number of neurons and rate values of the dropout layer.

## Feature selection methods
Recursive Feature Elimination (RFE) is a wrapper-type feature selection algorithm. RFE assigned scores for each features, and features that have the highest scores will be extracted.  Scikit-learn library \cite{RFE} is used to apply RFE with random forest.
