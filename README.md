# starbucks

Project Introduction:
This is starbucks portfolio exercise.

Installation and Library:
python==3.7.10
pandas==0.23.3
numpy==1.12.1
scikit-learn==0.19.1


Motivation:


Key process:

Difficulties:
The most difficult part of this exercise is the imbalanced dataset, in order to improve performance of model, several methods of handling imbalanced dataset are tried:
- undersampling of majority group
- oversampling of minority group
- smote

2 models are applied:
- randomforestclassifier
- adaboostclassifier

Overall, adaboostclassifier returns a better performance (higher recall, relatively higher f1 score) than randomforestclassifier for both. Although imbalanced dataset has been preprocessed, the results for label 1 is still not very satisfied.

Author: Ximin Juan

Acknowledgements: Udacity Data Scientist Program