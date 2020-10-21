# Prediction using Decision Tree Algorithm

#### For the ‘Iris’ dataset, create the Decision Tree classifier and visualize it graphically.
The main task on this dataset is to create an iris (name of a flower) classifier based on a given properties that are the sepal and petal size.


## Decision Tree algorithm :

Decision Tree algorithm belongs to the family of supervised learning algorithms. Unlike other supervised learning algorithms, the decision tree algorithm can be used for solving regression and classification problems too.
Decision trees use multiple algorithms to decide to split a node into two or more sub-nodes. <br>The creation of sub-nodes increases the homogeneity of resultant sub-nodes. In other words, we can say that the purity of the node increases with respect to the target variable. The decision tree splits the nodes on all available variables and then selects the split which results in most homogeneous sub-nodes.
 
![tree.png](https://media.geeksforgeeks.org/wp-content/uploads/dcsion.png) 

<b>Root Node:</b> This attribute is used for dividing the data into two or more sets. The feature attribute in this node is selected based on Attribute Selection Techniques.
<br><b>Branch or Sub-Tree:</b> A part of the entire decision tree is called branch or sub-tree.
<br><b>Splitting:</b> Dividing a node into two or more sub-nodes based on if-else conditions.
<br><b>Decision Node:</b> After splitting the sub-nodes into further sub-nodes, then it is called as the decision node.
<br><b>Leaf or Terminal Node:</b> This is the end of the decision tree where it cannot be split into further sub-nodes.
<br><b>Pruning</b>: Removing a sub-node from the tree is called pruning.<br>
![](https://cdn-images-1.medium.com/max/688/0*pb-1ufHK-OmR8k7r.png)
## Graphviz :

This package facilitates the creation and rendering of graph descriptions in the DOT language of the Graphviz graph drawing software (master repo) from Python.
Create a graph object, assemble the graph by adding nodes and edges, and retrieve its DOT source code string. Save the source code to a file and render it with the Graphviz installation of your system.
#### Installation
This package runs under Python 2.7, and 3.5+, use pip to install:<br>
$ pip install graphviz<br>
Download link : https://www.graphviz.org/download/

## PyDotPlus :

PyDotPlus is an improved version of the old pydot project that provides a Python Interface to Graphviz’s Dot language.

#### Installation :
$ pip install pydotplus

#### Documentation
User guide and API Reference can be found in: http://pydotplus.readthedocs.org/

