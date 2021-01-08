# Classifier-to-predict-diabetic-or-not-diabetic
Classifier using supervised machine learning algorithm which can accurately predict whether or not the patients in the dataset have diabetes. 

# Problem Statement 
The aim of this problem is to build a classifier using supervised machine learning algorithm
which can accurately predict whether or not the patients in the dataset have diabetes.

# Dataset Description  (CSV file included)
● Title: Pima Indians Diabetes Database
● Source: https://www.kaggle.com/uciml/pima-indians-diabetes-database
● Number of Instances: 768
● Number of Attributes: 9
● For Each Attribute: (all numeric-valued) 

# Data Preprocessing
● Importing the dataset into Pandas DataFrame format from .csv file.
● Splitting the dataset into the Training set and Test set using
  train_test_split.
● Taking care of missing data using SimpleImputer to fill ‘mean’
  value to Null values if any.
● Feature Scaling the dataset values using StandardScaler to bring
  all into same scale and to apply Principal component analysis
  (PCA) for dimensionality reduction to represent the result visually
  
 # Supervised learning techniques used
 Supervised learning techniques used for this particular classification problem are
 
# Logistic regression classifier
LR helps in finding the probability that a new instance belongs to a certain class. Since it is a
probability, the outcome lies between 0 and 1. Therefore, to use the LR as a binary classifier, a
threshold needs to be assigned to differentiate two classes. In this particular problem LR gives
accuracy score of 79.16%.

# Naive bayes classifier
Naïve Bayes (NB) is a classification technique based on the Bayes’ theorem.This classifier
assumes that a particular feature in a class is not directly related to any other feature although
features for that class could have interdependence. Using NB classifier we were able to get
79.16% of accuracy.

# K-nearest neighbors classifier
Unlike the NB technique, the KNN algorithm does not require to consider probability values.
The ‘K’ is the KNN algorithm is the number of nearest neighbours considered to take ‘vote’
from. The selection of different values for ‘K’ can generate different classification results for
the same sample object.For K=5, the model gave us the accuracy of 76.56%.

# Decision tree classifier
Decision tree models the decision logics i.e., tests and corresponds outcomes for classifying
data items into a tree-like structure. Although here we our case it doesn’t performs well due
to its greedy and deterministic nature and gives accuracy score of 65.62% only.

# Support Vector Classifier
(SVM) algorithm can classify both linear and non-linear data. After mapping data into
n-dimensional feature space where n is the number of features. It then identifies the
hyperplane that separates the data items into two classes with the accuracy score of
80.72% which is highest among all classifiers used.



# Result & Conclusion 
We found that the Support Vector Machine (SVM) algorithm predicted most accurately
(80.72 %) followed by the Naïve Bayes algorithm (79.16%).
However, the performance of the k-nearest neighbours classifier and logistic regression
classifier is also somewhere around the Naïve Bayes but the decision tree doesn't perform
well with this particular problem due to its greedy and deterministic nature.
This study provides a wide overview of the relative performance of different variants of
supervised machine learning algorithms for disease prediction. This important information of
relative performance can be used to aid researchers in the selection of an appropriate
supervised machine learning algorithm for their studies.

