# Unit-11
In these models of predicting credit risk using LendingClub data, a low risk loan is taken to be one where payment is current, whereas a high risk loan is where payment is late, in a grace period, or the loan is in default. A low risk loan is considered positive and high risk loan is considered negative for interpreting the confusion matrix and other metrics.

## Resampling
Naive Oversampling, SMOTE Oversamping, Cluster Centroid undersampling, and combined SMOTEENN sampling were used in testing linear regression models. The top perfomers in balanced accuracy, recall, and geometric mean are listed below.

Balanced accuracy: SMOTE Oversamping at 0.8389\
Recall: SMOTE Oversampling at 0.8658\
Geometric mean: Combined SMOTEENN sampling at 0.8387

## Ensemble
Balanced random forest and easy ensemble learners were tested. The top performers in balanced accuracy, recall, and geometric mean are listed below.

Balanced accuracy: Easy Ensemble Classifier at 0.9316\
Recall: Easy Ensemble Classifier at 0.9424\
Geometric mean: Easy Ensemble Classifier at 0.9315

Top 3 features for balanced random forest classifier:
1. total_rec_prncp
2. total_pymnt
3. total_pymnt_inv

### Contributors
```
Stephen Bernard
```