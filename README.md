**Credit_Card_Fraud_Detection_using_Sampling**

**Overview**

This project focuses on developing a credit fraud detection system using
machine learning techniques. The goal is to identify fraudulent credit
card transactions from a dataset containing both legitimate and
fraudulent transactions.

**Getting Started**

-   Importing the required libraries

-   Loading the dataset

-   Checking for the balanced or imbalanced dataset

![](vertopal_3f342ea5fc9f4f4f8838b675931321ec/media/image1.png){width="6.268055555555556in"
height="4.340277777777778in"}

-   As we see that the dataset is highly imbalanced , so we need to do
    resampling.

**Applying Resampling Techniques:**

-   **SMOTE (Synthetic Minority Over-Sampling Technique) :** which is a
    combination of oversampling and undersampling, but the oversampling
    approach is not by replicating minority class but constructing new
    minority class data instance via an algorithm.

```{=html}
<!-- -->
```
-   **Oversampling:** Random Oversampling: Increase the number of
    instances of the minority class by randomly duplicating existing
    instances.

-   **Undersampling:** Random Undersampling: Reduce the number of
    instances of the majority class by randomly removing instances.

**Dataset**

The dataset used for this project is sourced from \[provide the source
or link to the dataset\]. It contains a collection of transactions with
features such as transaction amount, timestamp, and customer
information.

# **Applying Different Sampling Techniques**

-   Random Sampling

-   Systematic Sampling

-   Stratified Sampling

-   Cluster Sampling

-   Time Logged Sampling

> **Applying Different models on all 5 samples and comparing the
> Accuracies**

  --------------------------------------------------------------------------
  Random         Systematic     Stratified     Cluster        Reservoir
  -------------- -------------- -------------- -------------- --------------
  Grid Search    0.875          0.937          0.854          0.953

  Naive Bayes    0.621          0.937          0.725          0.886

  Logistic       0.86           0.911          0.849          0.917
  Regression                                                  

  Random Forest  0.99481        0.994          0.994          0.994
  --------------------------------------------------------------------------

# **Results:**

-   Ramdom Forest Classifier gives best accuracy on all types of
    sampling.

**Evaluation Metrics:**

-   Accuracy

**Submitted By:**

-   Gaytri

-   Roll No: 102297019

