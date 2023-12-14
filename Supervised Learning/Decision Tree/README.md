## Decision Tree

Decision Tree is a supervised machine learning algorithm used for both classification and regression tasks. It works by recursively splitting the dataset into subsets based on the most significant attribute at each step. The goal is to create a tree structure where each internal node represents a decision based on an attribute, each branch represents the outcome of the decision, and each leaf node represents the final prediction or outcome. It usually contains the following key points:


1. Root Node: The initial node at the top of the tree is called the root node. It represents the entire dataset.
   
2. Splitting: At each internal node, the dataset is split into subsets based on a specific attribute (feature) and a corresponding threshold. The attribute and threshold are chosen to maximize the homogeneity or purity of the subsets.

3. Child Nodes: Each subset then becomes a child node, and the process is repeated recursively for each child until a stopping condition is met.

4. Leaf Nodes: The process continues until a predefined stopping criterion is reached. This could be a certain depth of the tree, a minimum number of samples in a node, or a threshold for purity. The terminal nodes of the tree are called leaf nodes, and they contain the final predicted outcome.

5. Predictions: When a new data point is introduced, it traverses the tree from the root to a leaf based on rules at each node. The prediction for the new data point is then based on the majority class or the average of the instances in the leaf node.


## Dataset Description

Adapted from https://www.kaggle.com/code/gantalaswetha/usa-housing-dataset-linear-regression/notebook. This dataset contains information of United States housing prices.
It contains 5000 rows with features such as average housing income and average housing age.

Detailed information regarding each feature can be found at the Kaggle website.
