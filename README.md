# Feature Selection and Pipelining Using Python

In this simple examples we are doing Feature Selection for Supervised Machine Learning Models.
The used Feature Selection Methods are:
A. Filter Method
  1. Correlation Method
  2. Variance Threshold Method
  3. Chi Square Method
  4. Fisher's Score Method
  5. Information Gain Index Method
B. Wrapper Method
  1. Forward Feature Selection
  2. Backward Feature Elimination
  3. Exhustive Feature Selection
  4. Recursive Feature Elimination
C. Embedded Method
  1. LASSO Regularization (L1) Method
  2. Random Forest Information Method

In this correlation-varience-L1.ipynb, there is also the implementation of machine learning pipeling.

# Implementation Details
The feature selection methods are listed against the dataset which they are used upon
A. TelecomData Set (given as TelecomData.zip) which is a collection od three other .csv files
  1. All Wrapper methods
  2. Random Forest Feature importance method
B. CarData Set (given as CarData.zip) which is a single .csv file with another .xlsx file for feature interpretation
  1. Correlation Method
  2. Varience Threshold Method
  3. LASSO Regularization (L1) Method
C. Iris Data set which is in build in sklearn python library
  1. Chi Square Method
  2. Fisher's Score Method
  3. Information Gain Index method
 
# Presentation 
  the presentation attached here is the overall view with some good points to know about the internal implementational details of
  feature selection methods and also a minimal implemenation of machine learning pipeling in python.

# Note
  to reduce the data cleaning burden , the implementations may seem to be scattered but the implemenations are really clean and with brief points
  in the presentation one can have basic knowledge of feature selection and machine learning pipeling.
