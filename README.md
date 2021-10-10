# Credit Card Fraud Detection System

A Data Science project on fraud detection system using machine learning algorithms


## Acknowledgements

 - [Kaggle Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
 
## Features

- ML model comparison
- Portrayed the differnece in results betweeen balanced and imbalanced data 
- Multiple performance metric
- Multiple ML algorithms to choose the best alternative

  
## Appendix

Notes from the dataset
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features and more background information about the data was not provided. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. 
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.


## Conclusion
1. The dataset was cleaned and the features were removed using PCA from the beginning because of the confidentiality reasons. This made woking on the model a bit difficult as the features were unknown.

2. The data is very unbalanced and all the models that were run using the dataset showed results which indicated overfitting.

3. I used SMOTE Tomek method to resample the dataset and made it balanced.

4. The models I worked on are Decision Tree, K-Nearest Neighbors (KNN), Logistic Regression, AdaBoost Classifier, Random Forest, and XGBoost

5. The best model was XGBoost classifier showing the best accuracy and F1 score in the balanced dataset.

6. The biggest problem is faced was while implementing SVM in the dataset. SVM took very long time to compute making it an unreasonable alternative for an ML model. I tried using differnt kernels within SVM (Linear and RBF ) but both took very long time to compute the results when the dataset was balanced.   
## Feedback

If you have any feedback, please reach out to me at pritampaul360@gmail.com

  
## Screenshots

![Screenshot](https://imgur.com/a/m8au9s7)
![Screenshot](https://imgur.com/a/cLuK8Wd)
![Screenshot](https://imgur.com/a/4C91sxY)
