# Python for Data-Science

Data science is an field that uses scientific methods, statistics, algorithms and various types of systems to understand and gain valuable insights from a given dataset.

# Pillars of Data Science

1. Domain Knowledge
2. Mathematics - Statistics, Probability, and Linear Algebra
3. Programming Knowledge

# Machine Learning Workflow

1. Data Acquisition: Accuring sufficient amount data from various sources. The acuired data should also be correct otherwise it might degrade the overall model. Some good websites for gathering dataset are: Kaggle, UCI, and Government Dataset (.gov.in for India)

2. Data Extraction/Cleaning: It is one of the most important and tideous task of the workflow. Removing unwanted/duplicate data from the dataset. There might be multiple columns that represent the same thing.
For eg: A data set contains the abbrevation and full form for a certain post as multiple coluns in the dataset, this might increase the time complexity and take more space. In some cases we see data that is 
irrelevant for the model. For eg: A dataset containg the employee ID and name in differnet columns is of no use as the Employee ID itself is sufficient to dffrentiate the data. 
Python offeres two libraries which assist in data extraction and cleaning namely: Numpy and Pandas
After cleaning the data, vizualization process takes place as it assists in providing a vivid view of the data. Statistical analysis is also performed to find the important relations. Matplotlib, Seaborn etc. are the libraries offered by python for data vizualization, scipy and pandas are used for performing statistical analysis
            
3. Data Transformation: It is also known as data preprocessing. There are two types of data:
  
  3.1 Numerical Data: Sometimes the data contains missing values, these values needs to be transformed before being used in the model. There are multiple ways to transform these values:
      
      3.1.1 Removing Missing Values: The columns/rows containing the missing values can directly be removed from 
      the dataset but this might result is loss of important data.
      
      3.1.2 Updating missing values: The missing values are updated in accordance to the available column values.
      Sklearn library(Imputer) can be used to update the missing values with the mean value of the column.
  
  3.2 Categorical Data: Sklearn libraries used to machine learning algorithm only support numerical data types. So in order to avail the required format the categorical data needs to be converted into numerical data.This can be achieved in the following ways:
      
      3.2.1 Label Encoding: Laber Encoder library can be used from the sklear.preprocessing class to label the data in numeric format. 
      This can aslo we achieved with the help of a dictionary. This technique is good for a small dataset but incase of a large dataset it
      can degrade the output as different values represet different level of importance.
      
      3.2.1 Dummies: Dummy variable can be created to assign the same level of importance by increasing the columns.

Feature Scaling is applied after processing the data in the required format. It is used to bring the mean and standard deviation is the specific range. It is important as it gives equal importance to each feature present in the dataset.

4. Data Modeling: The data is trained in the stage. There are two type of learning Supervised and Unsupervised Learning
  4.1 Supervised Learning contains the input and iutput values and the data is trained in accordance with the given data. Examples of supervised Learning are
  as follows:
    Classification: Classification is the process of categorizing the output as labels. For eg: Mail being classified as spam or not spam.
    Regression: Regression is the process of predicing a target value on basis of the given input features. For eg: Predicting annual rainfall
  4.2 Unsupervised learning has no specified output and it learns with experience. Examples of Unsupervised learning are as follows:
    Clustering: Clustering is the process of grouping similar data. For eg: segregating Gems/M&M on basis of colours
    Dimensionality Reduction: It is the process of reducing the number of features by obtaining a set of principal features.
Sklearn, pyTorch and Tensorflow are a few libraries that are mostly used for training the data.

5. Interpretation: The final stage of the process is to observe the output and i's evaluation. There are various measures for checking the accuracy of a model.
  5.1 Classification: Confusion matrix can be used for finding the accuracy. The accuracy is defined as the 
        Accuracy = (True Positive Values+False Potitive)/Total Values
  5.2 Regression: We can calculate the R2 score and Mean squared error to evaluate the performance of the model
Sklearn.metrics library is used for model evaluation in python

Some commonly used algorithms are as follow:
1. Linear Regression
2. Multivariable Regression
3. Polynomial Regression
4. Support Vector Machine
5. Decision Tree
6. Random Forest
7. Logistic Regression
8. K-Nearest Neighbours(KNN)
9. Artificial Neural Network(ANN)
10. Convolutional Neural Network(CNN)
11. Recurrent Neural Network(RNN)
