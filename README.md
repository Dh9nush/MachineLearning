# MachineLearning
Contains all Machine Learning Models
# 1)Bank Customer Churn Predictor
    -Predicting whether Customer would Churn or Not seeing past datas Of other Customers
    -Model used is Logistic Regressor
    -Since Churn Data is heavily imbalanced prediction is Biased at Threshold 0.5
    -after Certain Thresholding Model Started giving better results
    ![Screenshot (16)](https://user-images.githubusercontent.com/102205233/177283114-5810f7bc-1ffc-4472-985c-0b5c7681b21d.png)
    -Since Its import to find one who would Churn then not churn Our focus was at Recall value but also keeping model accuracy high
    -Recall&Accuracy vs Threshold value
    ![Screenshot (17)](https://user-images.githubusercontent.com/102205233/177283792-0b6e7c6b-914a-4460-b971-7568180fe540.png)      
    -Similary testing using Kfold method 
    ![Screenshot (18)](https://user-images.githubusercontent.com/102205233/177283953-6c4172fd-ed75-4e3b-a51d-8ef7411b145a.png)
    -Atlast Trying Backward selection or Reverse feature elimination 
    ![Screenshot (19)](https://user-images.githubusercontent.com/102205233/177284191-a7249d84-5a85-4529-8fb6-2a96b5fba8b3.png)
    -Conclusion:to get higher Recall  we are decreasing Threshold value and trading of precision value ,while also accuracy of model remains constants uptill certain threhsold,since Churn data is heavly biased that is 80:20 percentage ,it is totally upto business decision to choose Threshold value
 



