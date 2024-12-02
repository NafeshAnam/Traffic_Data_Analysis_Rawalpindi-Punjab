# Data Preprocessing and Model Training {Traffic_Data_Analysis_Rawalpindi-Punjab}

This repository contains a project for preprocessing an unclean dataset, training various machine learning models, and evaluating their performance using several metrics. The project is divided into multiple phases, each focusing on different aspects of model training and evaluation.

- Two models for two targets:
1. Injury Type
2. Patient Status 


# Project Structure

   - Data Preprocessing 
   - Model Training 
       - Logistic Regression
       - Decision Tree
       - Random Forest
       - XGBoost
       - Support Vector Machine (SVM)
       - Artificial Neural Network (ANN)
         


#  Data Preprocessing:


   - Apply necessary data cleaning and preprocessing steps to prepare the dataset for model training.
     

1.   Logistic Regression:

  - Train a Logistic Regression model on the training set.
  - Test the trained model on the test set.
  - Evaluate the model's performance using the following metrics:
  - Accuracy
  - Confusion Matrix
  - Precision
  - Recall
  - F1 Score

  
2.   Learning Curves:

- Plot the following learning curves for Logistic Regression:
  
   - Accuracy (y-axis) vs Solver (x-axis)
   - Accuracy (y-axis) vs Max_iter (x-axis)


  
# Training Additional Models

1. Data Preprocessing:

Ensure the dataset is preprocessed as required for training.

2.  Model Training:

- Train the following models on the training set:

   - Decision Tree
   - Random Forest
   - XGBoost
   - Support Vector Machine (SVM)


  
3.  Performance Evaluation:
   

- Evaluate the performance of the trained models on the test set using the following metrics:

    - Accuracy
    - Precision
    - F1 Score
    - Recall
    - Confusion Matrix
    - Prepare a comparison table for the models' performance, including Logistic Regression from above instructions.



4. Performance Plots:

- Plot the following curves:
   - Decision Tree: Accuracy (y-axis) vs Max_depth (x-axis)
   - SVM: Accuracy (y-axis) vs Kernel (x-axis)
   - Random Forest: Accuracy (y-axis) vs N_estimators (x-axis)
   - XGBoost: Accuracy (y-axis) vs Learning_rate (x-axis)
 

     
# Training an Artificial Neural Network (ANN)


1. Data Preprocessing:

 - Apply necessary data preprocessing to ensure compatibility with ANN.


  
2. Model Training:

 - Train an Artificial Neural Network (ANN) on the training dataset.


  
3. Performance Evaluation:

- Evaluate the performance of the ANN on the test set using the following metrics:
   - Accuracy
   - Precision
   - F1 Score
   - Recall
   - Confusion Matrix
   - Prepare a comparison table for all the models' performance, including Logistic Regression, Decision Tree, Random Forest, XGBoost, SVM, and ANN.
 
     
4. Performance Comparison Plots:

- Generate necessary plots to compare the performance of all algorithms.
  


# Notes

- Solver for Logistic Regression: {'lbfgs', 'liblinear', 'newton_cg', 'newton-cholesky', 'sag', 'saga'}
- Max_iter for Logistic Regression: {50, 100, 150, 200, 250, 300}
- Max_depth for Decision Tree: {4, 5, 6, 7, 8, 9}
- Kernel for SVM: {linear, poly, rbf, sigmoid}
- N_estimators for Random Forest: {10, 50, 100, 200}
- Learning_rate for XGBoost: {0.001, 0.01, 0.1, 1}


# Getting Started
- Clone the repository to your local machine.
- Ensure all dependencies are installed (see requirements.txt).
- Follow the instructions in each phase to preprocess the data, train the models, evaluate their performance, and generate plots.


# The Dataset:
   - https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/4VGTDR Links to an external site. 



# Contact

For any inquiries or support, please reach out at nafesh.anam07@gmail.com

