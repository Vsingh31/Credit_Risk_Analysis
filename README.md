# Credit_Risk_Analysis
## Overview of the analysis: 
The purpose of the loan prediction risk analysis is predict credit risk by using seversl machine learning models.Credit risk is very tough to predict.  
We adopted the following procedure:

* oversample the data using the RandomOverSampler and SMOTE algorithms.
* Undersample the data using the ClusterCentroids algorithm.
* Use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
* Compare two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

### Results:
* **RandomOverSampler Algorithms:** 

![Random](https://user-images.githubusercontent.com/90277142/149684055-01e42249-5fcf-4319-abe5-811638fba5a5.png)

 The balanced accuracy score is 64.2%.
 The high_risk precision is about 1% only with 63% sensitivity which makes a F1 of 2% only.
 Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 65%.
 
 * **SMOTE Model**
 
![SMOTE](https://user-images.githubusercontent.com/90277142/149684772-7f0da47b-a7d9-4c88-9ef9-fae8c85e123c.png)

 The balanced accuracy score is 63.8%.
 The high_risk precision is about 1% only with 64% sensitivity which makes a F1 of 2% only.
 Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 63%.
 
 * **ClusterCentroids Model**

![CCentroids](https://user-images.githubusercontent.com/90277142/149685165-aa701050-e2ea-43a5-b9c5-c67708b1ebe4.png)

 The balanced accuracy score is 51.4%.
 The high_risk precision is about 1% only with 59% sensitivity which makes a F1 of 1% only.
 Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 44%.
 
 * **SMOTEENN Model**

![Smoteeneen](https://user-images.githubusercontent.com/90277142/149686491-130582fe-e806-4e6b-bb05-811499795466.png)

 The balanced accuracy score is 64%.
 The high_risk precision is about 1% only with 59% sensitivity which makes a F1 of 1% only.
 Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 44%.
 
 * **Balanced Random Forest Classifier**

![brfc](https://user-images.githubusercontent.com/90277142/149686199-1dc48d16-22ac-41c1-bc68-0b5bc9fdaaf4.png)

 The balanced accuracy score is 64%.
 The high_risk precision is about 1% only with 59% sensitivity which makes a F1 of 1% only.
 Due to the high number of the low_risk population, its precision is almost 100% with a sensitivity of 44%.
 
 * **Easy Ensemble AdaBoost Classifier**
 
 ![easyessenbleadaboost](https://user-images.githubusercontent.com/90277142/149686432-7de967f6-edd5-46c5-9bea-f6fc14e8d838.png)

 The balanced accuracy score is 100%.
 The high_risk precision is about 100%  with 100% sensitivity which makes a F1 of 100% .
 Due to the high number of the low_risk population, its precision is 100% with a sensitivity of 100%.
 
Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
