# DECISION-TREE-IMPLEMENTATION
COMPANY : CODTECH IT SOLUTIONS

NAME : KARNATI BHAVYA

INTERN ID : CT2MTDM438

DOMAIN : Machine Learning

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH
#DESCRIPTION:
This project presents a supervised machine learning approach to classify breast cancer tumors as malignant or benign using a Decision Tree Classifier. The model is implemented in Python using the Scikit-learn library and trained on the built-in Breast Cancer Wisconsin Diagnostic Dataset, a well-known benchmark dataset in the medical and machine learning community.

A decision tree is a flowchart-like structure in which each internal node represents a test on a feature, each branch represents an outcome of the test, and each leaf node represents a class label. This type of model is highly interpretable and easy to visualize, making it ideal for healthcare-related problems where transparency is important.

🧬 Dataset Information
The dataset used in this project is loaded using Scikit-learn’s load_breast_cancer() function. It contains 569 samples with 30 numerical features derived from digitized images of breast mass cell nuclei. Each sample is labeled as either:

0: malignant (cancerous)
1: benign (non-cancerous)
Features include mean, standard error, and worst-case values for measurements such as radius, texture, perimeter, area, smoothness, compactness, and more.

The dataset is already cleaned and does not require any missing value handling, allowing a smooth workflow directly from feature extraction to model training.

# Model Implementation Steps
The steps followed in this project are as follows:

#Library Importing:
Libraries such as pandas, numpy, matplotlib, and Scikit-learn modules are imported for data handling, visualization, model creation, and evaluation.

#Loading and Preparing the Data:
The Breast Cancer dataset is loaded into a Pandas DataFrame. Features are stored in X and the target variable in y.

#Train-Test Split:
The dataset is split into training and testing sets in a 70:30 ratio using train_test_split(), ensuring the model is tested on unseen data.

#Model Training:
A DecisionTreeClassifier is initialized with the entropy criterion and a maximum depth of 4 to prevent overfitting. The model is trained on the training data using .fit().

#Tree Visualization:
The trained decision tree is visualized using plot_tree() from Scikit-learn. The tree is displayed with feature names and class labels, helping users interpret the decision paths taken by the model.

#Model Evaluation:
Predictions are made on the test data using .predict(). Evaluation is performed using:
Accuracy Score
Classification Report (precision, recall, F1-score)
Confusion Matrix
These metrics provide a clear picture of the model's performance on benign and malignant tumor classification.

# Results

The decision tree was able to achieve high accuracy on the test set, demonstrating its ability to generalize well on new data. The visualization provides transparency into how the model makes predictions, which is crucial in sensitive applications like medical diagnosis.

# OUTPUT

![Image](https://github.com/user-attachments/assets/85f07a34-d9bf-4d0b-b6b4-cb9e056297fd)

![Image](https://github.com/user-attachments/assets/b5c0bc9f-53d7-43b2-82d2-0c9c736a2236)
