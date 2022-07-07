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
 



