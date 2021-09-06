# Credit risk analysis through supervised machine learning

## Overview of the project:
* The objective of this project is to analyze the accuracy of different models and decide which one will provide the most accurate prediction of credit risk.

## Results:
1. Naive Random Oversampling
> ![NAIVE](https://user-images.githubusercontent.com/82552516/132258199-c7bc2252-ddf3-4ed5-9b7b-c12868a90887.png)
* Balanced Accuracy Score: 64.737%
* Precision High_Risk: 1%
* Precision Low_Risk: 100%
* Recall High_Risk: 69%
* Recall Low_Risk: 60%


2. SMOTE Oversampling
> ![SMOTE](https://user-images.githubusercontent.com/82552516/132258458-6566f981-ecfd-489d-8587-3d14bc224215.png)
* Balanced Accuracy Score: 66.216%
* Precision High_Risk: 1%
* Precision Low_Risk: 100%
* Recall High_Risk: 63%
* Recall Low_Risk: 69% 


3. Undersampling
> ![Under](https://user-images.githubusercontent.com/82552516/132258537-f1ea4f60-e464-4a25-8b83-075f1dc81711.png)
* Balanced Accuracy Score: 58.023%
* Precision High_Risk: 1%
* Precision Low_Risk: 100%
* Recall High_Risk: 58%
* Recall Low_Risk: 58% 


4. Combination Sampling
> ![Combination](https://user-images.githubusercontent.com/82552516/132258656-e3b97a9b-d44a-4b4a-a7d5-f9d4cd610fac.png)
* Balanced Accuracy Score: 67.754%
* Precision High_Risk: 1%
* Precision Low_Risk: 100%
* Recall High_Risk: 78%
* Recall Low_Risk: 57% 

5. Balanced Random Forest Classifier
> ![Balanced random](https://user-images.githubusercontent.com/82552516/132258737-683d7b7f-d546-474b-95ee-08cd1a490693.png)
* Balanced Accuracy Score: 78.855%
* Precision High_Risk: 3%
* Precision Low_Risk: 100%
* Recall High_Risk: 70%
* Recall Low_Risk: 87% 

6. Easy Ensemble AdaBoost Classifier
> ![Easy Ensemble](https://user-images.githubusercontent.com/82552516/132258836-2201ab45-35b1-44f9-b253-27289bfe3ad6.png)
* Balanced Accuracy Score: 93.166%
* Precision High_Risk: 9%
* Precision Low_Risk: 100%
* Recall High_Risk: 92%
* Recall Low_Risk: 94% 

## Summary:
* Based on the analysis of 6 different models, Easy Ensemble AdaBoost Classifier model provided the highest accuracy rate.




