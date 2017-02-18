# CancerPredictionModel
### Insight Data Challenge: 4 hour challenge
Breast Cell Cancer Prediction Model: Random Forest

This coding challenge explores, visualizes and builds a model from data on biopsied breast cells to examine and predict indicators of the cell being malignant or benign. The model finds accurate (97+%) ability to predict malignancy with two different models.

## Data Source
The data is taken from the University of California Irvine Machine Learning repository (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Original)), originally from University of Wisconsin hospitals.

## Modelling
This code explores RandomForestClassifier and ExtraTreesClassifier, finding similar accuracy with the two. Results are examined with f1 score, confusion matrix, AUC and AOC values.

## Caveats
* Important to differentiate the relative importance of false negatives (FN) and false positives (FP) in making the model recommmendation.
* I find that the data is insufficient to recommend the importance of one or more features over another.

## Reaching Further 
* The features should be additionally investigated for their high correlation
* Other models to investigate could include principle component analysis (PCA), Linear Support Vector machine (LSV), logistic regression, K-nearest neighbors 
