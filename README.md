# Credit_Risk_Analysis

### Overview:
We are looking at credit risk and trying to determine if we can predict which consumers are more likely to default on their loans.
We will be looking at several different models. We will train the models using the existing data and then compare which model 
predicts best the likely hood of default.

### Results:

* The Naive Random oversampling model: Our accuracy is 63%. The High Risk precision is 1% and the recall is 60%


 ![](https://github.com/tomstowell99/Credit_Risk_Analysis/blob/main/Resources/Random%20Sample.PNG)
 
* The SMOTE OverSampling Model. Our accuracy is 64%. The High Risk precision is 1% and the recall is 66%

   ![](https://github.com/tomstowell99/Credit_Risk_Analysis/blob/main/Resources/OverSample.PNG)
   
* The Cluster Undersampling model: Our accuracy is 64%. The High Risk precision was 1% and recall is 61%

   ![](https://github.com/tomstowell99/Credit_Risk_Analysis/blob/main/Resources/undersample.PNG)
   
* Combination of Over and Under Sampling using the SMOTEENN model
      Our accuracy was 62%. the High Risk precision was 1% and the recall was 69%.
      
    ![](https://github.com/tomstowell99/Credit_Risk_Analysis/blob/main/Resources/combination%20overandundersample.PNG)
    
    
  ### Summary:
  
  Our goal is the find a model with a high accuracy score as well as precision and recall. Precision measures 
  out of all the positive predicted, what percnetage is truly positive. Recall measures out of all the positive, 
  what percentage is truly positive. Because we are dealing with Credit risk. We want to emphasise the importance
  of recall accuracy. Based on the models I was able to get working we would select the Smote OverSampling Model.
  However I know the ADABoost classifier or the Random Forest Classifier probably would have resulted in a better
  model and chosen one of those.
  
