# Salary-Prediction-using-Machine-Learning-Models
**Objective:**
The objective of this project is to build a machine learning model that predicts whether a person's salary will be greater than $50,000 based on various features and attributes of the individual.

**Dataset:**
You will use a pre-collected dataset containing information about individuals, including their age, education level, occupation, work hours per week, marital status, etc. The dataset will be divided into features (input) and the target variable (output), which indicates whether the salary is greater than $50,000 (1) or not (0).

**Machine Learning Models:**
You will explore and implement four different machine learning algorithms to predict the salary status of individuals. The models to be used are as follows:

1. **Support Vector Classifier (SVC):**
    The Support Vector Classifier (SVC) is a supervised machine learning algorithm used for binary classification tasks. It aims to find the optimal hyperplane that best separates two classes in the feature space. The algorithm works by maximizing the margin between the two classes while penalizing misclassifications. SVC is effective in high-dimensional spaces and is versatile due to its ability to use different kernel functions, such as linear, polynomial, and radial basis function (RBF), to handle non-linearly separable data. However, SVC can be computationally expensive for large datasets and sensitive to the choice of hyperparameters.

2.**Logistic Regression:**
   Logistic Regression is a supervised machine learning algorithm used for binary classification tasks. It predicts the probability of an instance belonging to a particular class (e.g., 0 or 1). It uses the logistic function (sigmoid) to map predicted values between 0 and 1, making it suitable for probabilistic interpretations. The algorithm optimizes the model by minimizing the log loss function, which penalizes large errors. Logistic Regression is simple, interpretable, and efficient for large datasets but may struggle with complex relationships between features.

3. **Decision Tree Classifier:**
   The Decision Tree Classifier is a popular supervised machine learning algorithm used for classification tasks. It constructs a tree-like model where each internal node represents a test on a specific feature, and each leaf node corresponds to a class label. The algorithm recursively splits the data into subsets based on the selected features, aiming to minimize impurity or maximize information gain at each step. Decision trees are easy to interpret and visualize, making them suitable for understanding the decision-making process within the model. However, they can be prone to overfitting if not appropriately pruned or regularized.

4. **Random Forest Classifier:**
   The Random Forest Classifier is an ensemble learning algorithm that combines multiple decision trees to make predictions. It creates a multitude of decision trees during the training process and aggregates their predictions to produce a more accurate and robust result. Each tree is trained on a random subset of features and data samples, reducing overfitting and improving generalization. Random Forest is capable of handling large datasets and is less prone to overfitting compared to individual decision trees. It is widely used in various machine learning tasks, including classification and regression, due to its high accuracy and ability to handle complex data relationships.
