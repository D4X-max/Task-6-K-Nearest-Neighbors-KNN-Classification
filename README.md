# Task-6-K-Nearest-Neighbors-KNN-Classification

# STEP 1 - Choose a classification dataset and normalize features
I selected the Iris dataset for this project. I removed unnecessary columns, encoded the target labels, and normalized the feature values to ensure all features contribute equally during distance calculations.

# STEP 2 - Use KNeighborsClassifier from sklearn
I used the KNeighborsClassifier from scikit-learn to implement the K-Nearest Neighbors algorithm, which classifies data points based on the majority class of their nearest neighbors.

# STEP 3 - Experiment with different values of K
I trained and tested the model with several values of K (number of neighbors), comparing their performance to determine the optimal K for this dataset.

# STEP 4 - Evaluate model using accuracy, confusion matrix
I evaluated each model by calculating its accuracy and displaying the confusion matrix, which shows how well the classifier distinguishes between the different classes.

# STEP 5 - Visualize decision boundaries
I visualized the decision boundaries for the classifier using two features, allowing me to see how the KNN algorithm separates the classes in feature space.