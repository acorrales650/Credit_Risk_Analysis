# Credit_Risk_Analysis

## Purpose
The purpose of this analysis was to compare a data set by oversampling, undersampling, and using a combination method to determine credit risk. Once complete, the methods should be analyzed and assessed for effectiveness and a recommendation on which method should be used is to be provided. 


### Oversampling: Naive Random Oversampling
- Balanced Accuracy Score: 64.03%
- Precision
  - High Risk: 0.01
  - Low Risk: 1.00
- Recall
  - High Risk: 0.66
  - Low Risk: 0.62

### Oversampling: SMOTE
- Balanced Accuracy Score: 65.15%
- Precision
  - High Risk: 0.01
  - Low Risk: 1.00
- Recall
  - High Risk: 0.61
  - Low Risk: 0.69

### Undersampling: Cluster Centroids
- Balanced Accuracy Score: 54.42%
- Precision
  - High Risk: 0.01
  - Low Risk: 1.00
- Recall
  - High Risk: 0.69
  - Low Risk: 0.40

### Combination (Over and Under) Sampling
- Balanced Accuracy Score: 65.51%
- Precision
  - High Risk: 0.01
  - Low Risk: 1.00
- Recall
  - High Risk: 0.75
  - Low Risk: 0.56

### Balanced Random Forest Classifier
- Balanced Accuracy Score: 78.85%
- Precision
  - High Risk: 0.03
  - Low Risk: 1.00
- Recall
  - High Risk: 0.70
  - Low Risk: 0.87

### Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Score: 93.17%
- Precision
  - High Risk: 0.09
  - Low Risk: 1.00
- Recall
  - High Risk: 0.92
  - Low Risk: 0.94

## Summary
Based on the analysis of the data, there is a wide percentage gap in the 'Balanced Accuracy Score' with the lowest coming in at 64.03% balanced accuracy, the highest being 93.17 and the remainder of the methods falling in between. Futhermore, we see the same trend with respect to the 'Recall' numbers as well. Similarly, both high and low risk numbers have wide gaps ranging between 0.56 - 0.94. When we take a deeper look at our last method, the 'Easy Ensemble AdaBoost Classifier', it is apparent that with the high accuracy score of 93.17%, as well as the seemingly well balanced scores in the precision and recall, the 'Easy Ensemble AdaBoost Classifier' will be the best model for continued use. 
