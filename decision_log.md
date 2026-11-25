# Decision Log – Logistic Regression Model

## Decision 1: Dataset Selection
I selected the Student Performance Factors dataset because it contains information about students' study habits, attendance and academic performance.

## Decision 2: Feature Selection
I used student-related factors as input features and Pass_Fail as the target variable to predict whether a student will pass or fail.

## Decision 3: Data Preprocessing
I separated numerical and categorical features. I used imputation, scaling and one-hot encoding to prepare the data for model training.

## Decision 4: Train-Test Split
I used an 80:20 train-test split to train the model and evaluate its performance on unseen data.

## Decision 5: Model Selection
I selected Logistic Regression because the target variable has two categories: Pass and Fail.

## Decision 6: Decision Threshold
I used the default decision threshold of 0.5. A predicted probability of 0.5 or above is classified as Pass, otherwise it is classified as Fail.

## Decision 7: Model Evaluation
I evaluated the model using Accuracy, Precision, Recall, F1-score and a Confusion Matrix to understand its performance.
