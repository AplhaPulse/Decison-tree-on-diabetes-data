# Decision Tree Implementation: Fruit Variety Prediction

This repository provides a Python implementation of a decision tree classifier to predict fruit varieties based on their features.

## Purpose:

* Predicts the variety of a fruit (e.g., apple, banana, orange) based on input features like mass, color, and size.
* Demonstrates the application of decision tree algorithms for classification tasks.
* Provides insights into feature importance and decision-making processes.

## Implementation:

* Uses Python's `scikit-learn` library to build and evaluate the decision tree model.
* Employs `pandas` for data loading and manipulation.
* Visualizes the decision tree using `matplotlib` and `graphviz`.
* Includes functionality for tree pruning using `ccp_alpha` to control model complexity and prevent overfitting.
* Calculates and reports relevant evaluation metrics such as accuracy, precision, recall, and F1-score.

## Usage:

1.  Install dependencies: `pip install pandas scikit-learn matplotlib graphviz` (and Graphviz system installation if necessary).
2.  Place your fruit data in `fruit_data.csv` (or modify the script to read from your data source).
3.  Run the Python script: `python fruit_decision_tree.py`.
4.  Interpret output:
    * The script will display the decision tree visualization (`fruit_tree_visualization.png`).
    * It will also print the classification report containing precision, recall, F1-score, and support for each fruit variety.
    * The accuracy will also be reported.
    * The output will give you an idea of the trees complexity.

## Key Concepts:

* **Decision Tree:** A tree-like model that makes predictions by following decision rules derived from the data.
* **Feature Importance:** Measures the contribution of each feature to the prediction accuracy.
* **Pruning (ccp_alpha):** A technique to reduce the size of the tree and improve generalization.
* **Classification Metrics:** Measures the performance of the classification model (accuracy, precision, recall, F1-score).

## Output:

* Visualized decision tree (`fruit_tree_visualization.png`).
* Classification report (precision, recall, F1-score, support).
* Accuracy score.
* Information about the tree's depth and node count.
* Information about the parameters used to build the tree.
