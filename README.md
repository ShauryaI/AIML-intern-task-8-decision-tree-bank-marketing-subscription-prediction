# AIML-intern-task-8-decision-tree-bank-marketing-subscription-prediction
Interpretable ML using decision rules

## Dataset ##
UCI Bank Marketing Dataset - from ucimlrepo library
>>> pip install ucimlrepo

## Actions Performed ##
1. Load the dataset and check which features relate to customer subscription behavior.
2. Handle missing values or unknown categories and clean inconsistent text values.
3. Encode all categorical features using OneHotEncoding or LabelEncoding.
4. Split dataset into train-test sets with a fixed random_state.
5. Train Decision Tree Classifier and limit max_depth to avoid overfitting.
6. Visualize the tree using plot_tree() so splits are understandable.
7. Predict on test data and generate classification report.
8. Compare train accuracy vs test accuracy to detect overfitting issues.
9. Write 3 key rules from the decision tree that explain subscription behavior.

## Deliverables ##
Notebook: decision_tree.ipynb
Tree visualization image: bank_tree.png
Evaluation report: Last step in decision_tree.ipynb
