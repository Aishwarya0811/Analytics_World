#classification tree

In a standard classification tree, the idea is to split the dataset based on homogeneity of data. 
Lets say for example we have two variables: age and weight that predict if a person is going to sign up 
for a gym membership or not. 
In our training data if it showed that 90% of the people who are older than 40 signed up, 
we split the data here and age becomes a top node in the tree. 
We can almost say that this split has made the data "90% pure". 
Rigorous measures of impurity, based on computing proportion of the data that belong to a class, 
such as entropy or Gini index are used to quantify the homogeneity in Classification trees.

#Regression Tree 

In a regression tree the idea is this: since the target variable does not have classes, 
we fit a regression model to the target variable using each of the independent variables. 
Then for each independent variable, the data is split at several split points. 
At each split point, the "error" between the predicted value and the actual values is squared to get a "Sum of Squared Errors (SSE)". 
The split point errors across the variables are compared and the variable/point yielding the lowest SSE is chosen as the root node/split point. 
This process is recursively continued.
