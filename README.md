# Credit_Risk_Analysis

# Overview 

In this project, we have utilized a credit card credit dataset from our client, LendingClub, who wants us to utilize several machine learning models in order to predict credit risk. Depending on the performance of the models, they may be used by LendingClub to aid in future loan lending practices. The different types of sampling/classifier models are as follows: 

1. Naive Random Oversampling
2. SMOTE Oversampling
3. Cluster Centroids Undersampling
4. SMOTEEN (Oversampling/Undersampling)
5. Balanced Random Forest
6. Easy Ensemble AdaBoost Classifier

# Results 

1. Naive Random Oversampling

The first type of sampling that we utilized was Naive Random Sampling. We created training variables to test how well this sampling algorithm worked. Below, we have outlined the necessary data points to see how well the approach worked. 

![]()

Based on this, we can see that our balanced accuracy for this type is 64%. Furthermore, we can see that our precision is at 99% and our recall/sensitivity is at 62%.

2. SMOTE Oversampling

The second type of sampling that we utilized was SMOTE Oversampling. We created training variables to test how well this sampling algorithm worked. Below, we have outlined the necessary data points to see how well the approach worked. 

![]()

Based on this, we can see that our balanced accuracy for this function is 65%. Furthermore, we can see that our precision is at 99% and our recall/sensitivity is at 69%. This matches our first sampling type, Naive Random Sampling, in balanced accuracy, but the recall for this type yields slightly higher results. 

3. Cluster Centroids Undersampling

The third type of sampling that we utilized was Cluster Centroids Undersampling. We created training variables to test how well this sampling algorithm worked. Below, we have outlined the necessary data points to see how well the approach worked. 

![]()

Based on this, we can see that our balanced accuracy is somewhat lower at 54%. Furthermore, we can see that our precision is at 99% and our recall/sensitivity is at 42%. Compared the previous two sampling types, this sampling approach yielded the least in each data category with this dataset. 

4. SMOTEEN (Oversampling/Undersampling)

The fourth type of sampling that we utilized was SMOTEEN (Oversampling/Undersampling). We created training variables to test how well this sampling algorithm worked. Below, we have outlined the necessary data points to see how well the approach worked. 

![]()

Based on this, we can see that our balanced accuracy is somewhat low at 64%. Furthermore, we can see that our precision is at 99% and our recall/sensitivity is at 42%. This matches the first two sampling types, Naive Random Sampling and SMOTE sampling, but has a low recall/sensitivity like the Cluster Undersampling. 

5. Balanced Random Forest

The first classifier type of sampling that we utilized was Balanced Random Forest. We created training variables to test how well this sampling algorithm worked. Below, we have outlined the necessary data points to see how well the approach worked. 

![]()

Based on this, we can see that our balanced accuracy is somewhat higher at 78%. Furthermore, we can see that our precision is at 99% and our recall/sensitivity is at 87%. This outpaces each of the previous sampling types but is a step behind the Easy Ensemble AdaBoost Classifier sampling model.

6. Easy Ensemble AdaBoost Classifier

The second classifier type of sampling that we utilized was Easy Ensemble AdaBoost Classifier. We created training variables to test how well this sampling algorithm worked. Below, we have outlined the necessary data points to see how well the approach worked. 

![]()

Based on this, we can see that our balanced accuracy is somewhat higher at 93%. Furthermore, we can see that our precision is at 99% and our recall/sensitivity is at 94%. This sampling type dwarfed the rest in terms of accuracy amongst this dataset and our test variables. 

# Summary 

Based on the credit risk dataset, most of our machine learning sampling models do not perform well in regard to predicting credit risk. Among the four sampling algorithms, we can see that they all perform about the same as each other. All were very precise (around 99%) but were low in their recall and accuracy variables. The two classifier models stood out in most categories. The Balanced Random Forest classifier outperformed the four algorithms. The Easy Ensemble AdaBoost Classifier performed the best overall recall for high-risk applicants and the highest precision. Even though it does, we have to mention that the F1 score is still very low so this model is much better than the others. More will need to be done to create a better model, but it is recommended that this one be currently used.
