# A Replication Study: Heart Failure Risk Factors and Survival
## Data
The public dataset used for this study can be downloaded from the UCI Machine Learning Repository at http://archive.ics.uci.edu/dataset/519/heart+failure+clinical+records.
The dataset contains the medical records of 299 patients with left ventricular systolic heart failure who had had previous heart failure and were in classes III or IV of the New York Heart Association classification of the stages of heart failure.
## Results
A previous study using the same dataset was done by Chicco and Jurman (2020) using R. I replicated the study using Python. 
My objective was to improve the modelling results of the previous study by first, balancing the dataset using SMOTE + ENN, second using GridSearchCV to tune the hyperparameters of the classifiers tested, and third, using 'select from model' to assess the highest ranked risk factors to use in the model.
The final random forest model fitted to the five key risk factors achieved an MCC of 0.885, an F1 score of 0.917, a balanced accuracy of 0.927, and a recall of 0.865 which exceeded the best performance results of the previous study.
