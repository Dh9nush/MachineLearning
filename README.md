# MachineLearning
Contains all Machine Learning Models
# 1)Bank Customer Churn Predictor
    -Predicting whether Customer would Churn or Not seeing past datas Of other Customers
    -Model used is Logistic Regressor,Decision Tree

    -Since Churn Data is heavily imbalanced prediction is Biased at Threshold 0.5
    -after Certain Thresholding Model Started giving better results
![Screenshot (16)](https://user-images.githubusercontent.com/102205233/177284947-9ceb28fe-28f6-4265-af4e-c76f980c387b.png)

    -Since Its import to find one who would Churn then not churn Our focus was at Recall value but also keeping model accuracy high
    -Recall&Accuracy vs Threshold value
![Screenshot (17)](https://user-images.githubusercontent.com/102205233/177284988-d7f08a00-975b-4a21-abaf-32752dbb64cf.png)

    -Similary testing using Kfold method 
![Screenshot (18)](https://user-images.githubusercontent.com/102205233/177285033-7ac6126d-5b40-4b00-b682-c218404dba04.png)

    -Atlast Trying Backward selection or Reverse feature elimination 
![Screenshot (19)](https://user-images.githubusercontent.com/102205233/177285107-9b7d8d30-2e7d-4b57-bbeb-01d775f2af7d.png)

    -Conclusion:to get higher Recall  we are decreasing Threshold value and trading of precision value ,while also accuracy of model remains constants uptill certain threhsold,since Churn data is heavly biased that is 80:20 percentage ,it is totally upto business decision to choose Threshold value
    
    
    
   
# 2) NyCTaxi_Trip_Time_Project
    - Predicting ride time taken by trips to check availibity of taxi in Newyork center
    - Exploratery data Analysis Results
![Screenshot (23)](https://user-images.githubusercontent.com/102205233/178106459-99704945-e12d-48ac-891b-c5123416db2d.png)
![Screenshot (24)](https://user-images.githubusercontent.com/102205233/178106387-e9a3fea2-399b-4956-8a51-eaadd1dbc02d.png)
![Screenshot (25)](https://user-images.githubusercontent.com/102205233/178106393-7cb44329-9440-474c-84b2-1cb551185af8.png)
    - Correlation Heatmap
![Screenshot (26)](https://user-images.githubusercontent.com/102205233/178106399-4e599417-62db-4ca1-aed9-b5923ac67fb0.png)
    - Heatmap Map of Heavysites of trips takes place
![Screenshot (27)](https://user-images.githubusercontent.com/102205233/178106408-cdb5c3b3-8567-4901-89d3-5a6ab8caa752.png)



Conclusion: LinearRegresser Model Perform kinda Low then Decision Tree has data has high non  linearity in between data sets
![Screenshot (28)](https://user-images.githubusercontent.com/102205233/178106349-917f5eb4-876c-4993-a642-ae0937c16cf2.png)


# 3) Employee_Attrition_Prediciton
    - Prediting Whether Employee will Leave the company or not
    - Exploartery Data Analysis Results
![Screenshot (34)](https://user-images.githubusercontent.com/102205233/180636852-4149ac3a-555a-4f18-9ebb-7d454131d9ee.png)
![Screenshot (30)](https://user-images.githubusercontent.com/102205233/180636857-0c55287a-417c-4ee9-9c0c-f16a184448b2.png)
![Screenshot (33)](https://user-images.githubusercontent.com/102205233/180636851-bba56a09-1195-49ce-8ba5-04c64ca41d3a.png)
![Screenshot (32)](https://user-images.githubusercontent.com/102205233/180636861-c709f97c-bb39-4be7-82fc-8cfe61ae9f64.png)
![Screenshot (31)](https://user-images.githubusercontent.com/102205233/180636866-d21e8959-ac46-4459-bc8f-5d0e85027570.png)
   - Models used : LogisticRegression ,Decision Tree,RandomForest,SVM,KNN
![Screenshot (35)](https://user-images.githubusercontent.com/102205233/180636907-e658fa5c-1ce8-4eac-a6a9-4f6a0050577b.png)
   # As Expected Tree Models Outperform Others as data had many non linear Factors

  
   
   



