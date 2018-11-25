# Introduction to Random Forests

Decision trees are a powerful and popular machine learning technique. The basic concept is very similar to trees that we commonly use to aid decision-making.

Machine Learning techniques enables us to automatically construct a decision tree that tells us what outcomes we should predict in certain situations.

The decision tree algorithm is a supervised learning algorithm -- we first construct the tree with historical data, and then use it to predict an outcome. 
- One of the major advantages of decision trees is that they can pick up nonlinear interactions between variables in the data that linear regression can't.

The following work is a walk through of the building blocks of making a decision tree automatically.

We'll be looking at individual income in the United States. 
The data is from the 1994 census, and contains information on an individual's 
- marital status
- age 
- type of work, and more. 

The target column, or what we want to predict, is whether individuals make less than or equal to 50k a year, or more than 50k a year. The dataset can be accessed from the [University of California, Irvine's website](http://archive.ics.uci.edu/ml/datasets/Adult).


Following projects shows the implementation and application of Decision Trees on the same data set -

- [Introduction to Decision Trees](https://github.com/ajdatahub/ProjectDS/blob/master/Decision%20Trees/Introduction%20to%20Decision%20Trees.ipynb)

- [Applying Decision Trees](https://github.com/ajdatahub/ProjectDS/blob/master/Decision%20Trees/Applying%20Decision%20Trees.ipynb)

In these projects, I have learned about how decision trees are constructed and how to use them most effectively.


The most powerful tool for reducing decision tree overfitting is called the random forest algorithm. In the current project, we'll learn how to construct and apply Random Forests.
