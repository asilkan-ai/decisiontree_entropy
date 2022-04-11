# Entropy based decision trees analysis

Data Set Information:

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

Dataset Link: https://archive.ics.uci.edu/ml/datasets/bank+marketing

*Decision Tree :* 
Decision tree is the most powerful and popular tool for classification and prediction. A Decision tree is a flowchart like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label.

![decision](https://user-images.githubusercontent.com/73762823/162845406-98423547-990b-4125-80be-15ed6b548be4.png)

*Entropy :*
Entropy is an information theory metric that measures the impurity or uncertainty in a group of observations. It determines how a decision tree chooses to split data.

![entropy](https://user-images.githubusercontent.com/73762823/162846029-1dbfd530-f1a1-4039-b5e7-aa13b986b612.png)

Features with low entropy settle closer to the root of the tree.

This code is written for entropy but different algorithms can be easily implemented by changing the parameter (Gini etc.)
