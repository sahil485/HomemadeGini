# HomemadeGini
A Gini-based CART model created from-scratch for classification. The model uses a contrived, randomely generated dataset for training. 

Steps Taken:
  1) Write a function that given a list, finds the entry that serves as the best split point in terms of it's Gini cost function value.
  2) Implement recursive binary splitting to create splits at the optimal split points found using the function in step 1
  3) Create a nested list of split points and their probability-based predictions at the leaf nodes
  4) Flatten this list using a recursive depth-first traversal 
  5) Iterate through the flattened list recursively to create the tree out of Node objects with value, index, left, right, and prev attributes
  6) Write a prediction function using the conditions in the nodes of the decision tree to evaluate an input sample and predict it's class. 
