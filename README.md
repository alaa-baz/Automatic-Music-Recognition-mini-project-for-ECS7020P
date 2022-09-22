# Automatic Music Recognition (Machine learning)

This project used machine learning to detect music recognition automatically by using the MLEnd Hums and Whistles dataset. This dataset has hums and whistles for some famous songs. For more information, you can find this dataset at https://www.kaggle.com/datasets/jesusrequena/mlend-hums-and-whistles.

This project is divided into two tasks:
Binary Classification:  this task classified data into two songs: Potter and Star Wars. Some data (songs) have been used under Potter and Star Wars class. The pipeline has been applied separately with popular binary classification algorithms, LogisticRegression, DecisionTreeClassifier, and Support Vector Machine (SVC). The Pipeline with SVC achieved the highest performance. 

Multiclass Classification:  this task predicted songs into five classes: Frozen, Hakuna, Panther, Potter, and Rain. This task used popular algorithms for Multiclass after applying SMOTE technique, which are DecisionTreeClassifier, RandomForestClassifier, and pipeline with KNeighborsClassifier. Also, GridSearchCV has been tried using, but it did not improve the result. However, the pipeline with KNeighborsClassifier got a better result. 
