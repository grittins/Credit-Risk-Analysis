# Credit-Risk-Analysis

## Resources
Data: 
- LoanStats_2019Q1.csv

Software: 
- Python 3.7 

Data Manipulation and Analysis: 
- numpy
- pandas
- sklearn
- imblearn

## Overview of the Analysis

Credit card credit dataset is from LendingClub, a peer-to-peer lending services company. 
Imbalanced-learn and scikit-learn libraries are used to build and evaluate models using resampling. 

The following tasks are completed: 
- Oversampling using RandomOverSampler and SMOTE algorithms
- Undersampling using the ClusterCentroids algorithm
- A combination of over and undersampling using the SMOTEENN algorithm
- To reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier used to predict credit risk

## Results

| Balanced Accuracy Scores | | 
| ----------- | ----------- |
| Naive Random Oversampling | 0.67 |
| SMOTE Oversampling | 0.66 |
| Cluster Centroids | 0.54 |
| SMOTEENN | 0.64 |
| Balanced Random Forest Classifier | 0.79 |
| Easy Ensemble AdaBoost Classifier | 0.93 |

### Imbalanced Classification Report

- Naive Random Oversampling

<img width="552" alt="Screen Shot 2022-10-10 at 11 18 16 PM" src="https://user-images.githubusercontent.com/104872971/194989550-41dcaf3d-2741-4f09-a3cf-c4aeadd61786.png">

- SMOTE Oversampling	

<img width="551" alt="Screen Shot 2022-10-10 at 11 18 03 PM" src="https://user-images.githubusercontent.com/104872971/194989515-f6d1198f-de29-4bd8-9aeb-5281a0056372.png">

- Cluster Centroids

<img width="553" alt="Screen Shot 2022-10-10 at 11 17 49 PM" src="https://user-images.githubusercontent.com/104872971/194989498-a77cadb1-73fe-418b-952f-2b274e85e802.png">

- SMOTEENN

<img width="555" alt="Screen Shot 2022-10-10 at 11 17 24 PM" src="https://user-images.githubusercontent.com/104872971/194989486-92e585a2-4386-4840-9ade-52f8a3be2ee4.png">

- Balanced Random Forest Classifier	

<img width="599" alt="Screen Shot 2022-10-10 at 11 16 58 PM" src="https://user-images.githubusercontent.com/104872971/194989461-faf8914e-c74d-42eb-a4a5-7938afde5722.png">

- Easy Ensemble AdaBoost Classifier

<img width="597" alt="Screen Shot 2022-10-10 at 11 16 34 PM" src="https://user-images.githubusercontent.com/104872971/194989441-b8d0e728-f13e-47d2-b85e-c596de4963ab.png">





