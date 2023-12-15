# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

- The objective of this analysis was to develop a model capable of assessing the creditworthiness of borrowers using a dataset derived from the past lending transactions of a peer-to-peer lending services company. The primary aim is to create a model that can predict and classify loans deemed as low risk ('0') as well as those identified as high risk ('1').

Results

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

- Precision:

Precision for the "Healthy" class (0) is 1.00, which means that when the model predicts an instance as "Healthy," it is correct 100% of the time.
Precision for the "High Risk" class (1) is 0.87. This indicates that when the model predicts an instance as "High Risk," it is correct 87% of the time.Recall (Sensitivity or True Positive Rate):

- Recall for the "Healthy" class (0) is 1.00, indicating that the model is capturing all instances of the "Healthy" class in the dataset.

Recall for the "High Risk" class (1) is 0.89. This means the model is capturing 89% of the actual "High Risk" instances.
F1-Score:

- The F1-score is the harmonic mean of precision and recall. For the "Healthy" class (0), it is 1.00, reflecting a balance between precision and recall.
The F1-score for the "High Risk" class (1) is 0.88, representing a harmonic mean of precision and recall for the "High Risk" class.
Support:

- The support indicates the number of instances in each class. There are 18,759 instances of the "Healthy" class and 625 instances of the "High Risk" class.

- Accuracy:
The overall accuracy of the model is 0.99, which means that it correctly predicts the labels for 99% of the instances in the dataset.
Macro Average and Weighted Average:

- The macro average calculates the average of the metrics without considering class imbalances. In this case, the macro average for precision, recall, and F1-score is 0.94.
The weighted average gives more weight to the class with a larger number of instances. The weighted average for precision, recall, and F1-score is 0.99.

## Summary

- In summary, the model is achieving high accuracy and good balance between precision and recall for both classes. However, it's important to consider the context of the problem and whether specific considerations for false positives or false negatives are critical. The class imbalance might be a factor to consider, especially for the "High Risk" class with a smaller number of instances.
