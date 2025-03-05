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




PROBLEM STATEMENT 
-------------------------------------------------

In the banking sector, acquiring new deposits is crucial for maintaining liquidity and supporting lending activities. However, predicting whether a customer will make a future deposit remains a challenge due to diverse customer profiles, economic conditions, and behavioral patterns.

The objective of this project is to build a Decision Tree-based Classification Model that accurately predicts whether a customer is likely to deposit money in the bank in the future. By analyzing historical customer data — including demographics, past interactions with the bank, and financial history — the model will classify customers into two categories:

Class 1: Customer will make a deposit.
Class 0: Customer will not make a deposit.
This predictive model will help the bank:

Enhance marketing strategies by targeting potential depositors.
Optimize resource allocation by focusing on high-probability customers.
Improve customer engagement through personalized offers and communications.
The Decision Tree algorithm is chosen for its interpretability, as the bank's management team can easily understand the logic behind each prediction. The model’s performance will be evaluated using key classification metrics such as Accuracy, Precision, Recall, F1 Score, and AUC-ROC Curve.
