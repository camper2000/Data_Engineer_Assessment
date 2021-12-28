# Section 4: Charts and APIs

### Methodoloy Explaination
This Machine Learning Model adopts **k-nearest neighbors** algorithm to train the model.
Other algorithms are considered not suitable for this case:
1. Since buying price, the dependent variable, is categorical, **Linear Regression** is not suitable;
2. Since buying price has four values, **Decision Tree** and **Support Vector Machine** algorithms, which are more suitable for binary value prediction, is not adopted.

### Files Explanation:

- Machine_Learning_Car_Price.ipynb - This script contains the code to build a model to predict the car buying price for given parameters.
- car.data - The Car Evaluation Data Set;
