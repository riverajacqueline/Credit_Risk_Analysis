# Credit_Risk_Analysis

## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, different techniques are used to train and evaluate models with unbalanced classes.

## Results
### Naive Random Oversampling:
![image](https://user-images.githubusercontent.com/103764279/185662723-8cdf1384-8e06-4bcd-bed2-380566974179.png)
![image](https://user-images.githubusercontent.com/103764279/185662945-db7f1211-7c34-4280-817b-b798726e73bd.png)

- Balanced Accuracy: 65%
- Precision: High Risk .01, Low Risk 1.00
- Recall: High Risk .72, Low Risk .59

### SMOTE Oversampling:
![image](https://user-images.githubusercontent.com/103764279/185663635-6842db2c-7e47-40de-a3b1-3f8dfc265e7d.png)
![image](https://user-images.githubusercontent.com/103764279/185663716-8094d623-7d6b-4984-8698-32baebcaace4.png)

- Balanced Accuracy: 66%
- Precision: High Risk .01, Low Risk 1.00
- Recall: High Risk .63, Low Risk .69

### Undersampling Cluster Centroid:
![image](https://user-images.githubusercontent.com/103764279/185664669-eaf560b8-29f7-4bbe-827f-ca875f583973.png)
![image](https://user-images.githubusercontent.com/103764279/185664737-c1c85c9c-3f9b-4bec-868b-60790b8ac51e.png)

- Balanced Accuracy: 66%
- Precision: High Risk .01, Low Risk 1.00
- Recall: High Risk .69, Low Risk .40

### SMOTEENN Combination Over and Under Sampling:
![image](https://user-images.githubusercontent.com/103764279/185665210-2fad341c-1d78-4b28-9a41-1aee793cebc6.png)
![image](https://user-images.githubusercontent.com/103764279/185665347-00551715-b2f3-4b2b-9ffd-9d7cc687ab41.png)

- Balanced Accuracy: 54%
- Precision: High Risk .01, Low Risk 1.00
- Recall: High Risk .72, Low Risk .57

### Balanced Random Forest Classifier:
![image](https://user-images.githubusercontent.com/103764279/185665889-cc157163-0d9d-4a4d-94b5-f826fbd8ed29.png)
![image](https://user-images.githubusercontent.com/103764279/185665967-e5566874-71ad-4d51-8ed2-a7b43437aa18.png)

- Balanced Accuracy: 83%
- Precision: High Risk .03, Low Risk 1.00
- Recall: High Risk .77, Low Risk .88

### Easy Ensemble AdaBoost Classifier:
![image](https://user-images.githubusercontent.com/103764279/185666857-1c8ce81a-e9d2-46d4-aab1-a31c1d707572.png)
![image](https://user-images.githubusercontent.com/103764279/185666928-0759190f-9696-4a20-9d99-3bdb4c25af9d.png)

- Balanced Accuracy: 93%
- Precision: High Risk .07, Low Risk 1.00
- Recall: High Risk .91, Low Risk .95

## Summary
The model I would recommend would be the Easy Ensemble. The balanced accuracy has a high score was 93%, as well as a good balance of precision and recall scores. Having a good balance between scores allows accurate prediction of credit risk.
