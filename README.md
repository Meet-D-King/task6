# Task 6: K-Nearest Neighbors (KNN) for Iris Classification

## Overview
This project implements the K-Nearest Neighbors (KNN) algorithm to classify species of the Iris flower. The primary objectives are to understand the core mechanics of this instance-based learner, the importance of hyperparameter K, the critical need for feature scaling, and to visualize the resulting decision boundaries.

## Project Workflow
1.  **Data Preparation:** The Iris dataset was loaded from Scikit-learn. The features were then standardized using `StandardScaler`, a crucial step for a distance-based algorithm like KNN.
2.  **Optimal K Selection:** The "Elbow Method" was used to find the best value for the hyperparameter K. Models were trained for K values from 1 to 40, and their error rates were plotted. Based on the plot, K=5 was chosen for the final model.
3.  **Model Training & Evaluation:** The final KNN classifier was trained with K=5. It achieved 100% accuracy on the test set for this particular split, and its performance was detailed with a confusion matrix and classification report.
4.  **Decision Boundary Visualization:** A key part of the project was visualizing how KNN makes decisions. A 2D plot was created using two features ('sepal length' and 'sepal width') to show the complex, non-linear decision boundaries that the algorithm forms.
