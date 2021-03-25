# SECOM_Dataset_Analysis

## Product entity yield type prediction

**Domain:** Semiconductor manufacturing process

**Business Context**
A complex modern semiconductor manufacturing process is normally under constant surveillance via the monitoring of signals/variables collected from sensors and or process measurement points. However, not all of these signals are equally valuable in a specific monitoring system.
The measured signals contain a combination of useful information, irrelevant information as well as noise. Engineers typically have a much larger number of signals than are actually required. If we consider each type of signal as a feature, then feature selection may be applied to identify the most relevant signals. The Process Engineers may then use these signals to determine key factors contributing to yield excursions
downstream in the process. This will enable an increase in process throughput, decreased time to learning and reduce the per unit production costs. These signals can be used as features to predict the yield type. And by analyzing and trying out different combinations of features, essential signals that are impacting the yield type can be identified.

**Objective**
We will build a classifier to predict the Pass/Fail yield of a particular process entity and
analyze whether all the features are required to build the model or not.

Secom data set can be reached by the following site:
http://archive.ics.uci.edu/ml/datasets/secom

As a special issue in manufacturing research field, the defect detection of wafer products has always been an eye catcher in academia and challenge in daily production. In order to improve the accuracy of defect detection and free manpower from heavy labouring, a complex modern semi-conductor manufacturing process is normally under consistent surveillance via the monitoring of signals/variables collected from sensors and or process measurement points, providing sufficient samples to exvacate patterns from the past. However, not all of these signals are equally valuable in a specific monitoring system. The measured signals contain a combination of useful information, irrelevant information as well as noise. Meanwhile, defective wafers are rare compared to the qualified ones in practice. As a result, th data set shows an obvious characteristic that the ratio between different classes are imbalanced which may lead to severe bias of the classifier.
Hence, three different scientific problems are hidden inside this data set, which are the Feature Selection problem, the Imbalanced Learning problem and the Classification problem. Before implementing specific solutions to solve these problems, raw data also needs cleansing to filter those 'Nan' and blanks in the data set. After the data preprocessing process, different solutions towards three scientific problems can be choosed and optimized. Finally, by combining those locally optimized methods with different ordering stategies, the accuracy of fault detection can be optimized as a whole.

**The detailed attributes of the data set is shown as follows:**
Number of Instances:1567
Number of Attributes:591
Missing Values?:Yes
Attribute Characteristics:Real
Number of Classes:2
Imbalanced ratio: approximately 15:1
Associated Tasks:Data Cleansing, Feature Selection, Classification, Imbalaced Learning

**Learning Outcomes**
Exploratory Data Analysis
Feature Importance
Feature Selection
Over Sampling (SMOTE)
Grid Search
PCA
Decision Tree
Random Forest
XGBOOST
Gradient Boosting
Naive Bayes
KNN
SVM
Logistic regression
Pipeline
Handling Outliers (IQR & Z-Score)
Filling Missing Values
Data Visualization
