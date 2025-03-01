DECISION TREE
--------------------------------------------


A decision tree is a supervision machine lrarning algo. used for both classification and regression task. it works by splitting data into 
subset works by splitting data into subsets based on the value of input features, forming a tree-like structure.

🌿 Key components:
---------------------------------------------
Root Node: The starting point of the tree, representing the entire dataset.
Internal Nodes: Represent decisions or tests on features (e.g., "Is age > 30?").
Leaf Nodes: Final outputs or classes (e.g., "Approved" or "Denied").
Branches: Paths that connect nodes, showing the outcomes of decisions.


🔍 How it works:
-----------------------------------------------


Splitting: The algorithm chooses a feature and a threshold to split data into two or more groups.
Impurity Calculation: It uses metrics like:
Gini Impurity: Measures how often a randomly chosen element would be incorrectly classified.
Entropy: Measures information gain.
Recursive Splitting: The process repeats until a stopping criterion is met — like reaching a maximum depth or having a minimum number of samples per leaf.
Pruning: Optional step to remove unnecessary branches, reducing overfitting.
