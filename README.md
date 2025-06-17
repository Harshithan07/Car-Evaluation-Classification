# Car-Evaluation-ClassificationCar Evaluation Classification – Predicting Vehicle Ratings with Multiclass Models

## ABOUT THE PROJECT:
This project focused on predicting car evaluations (unacceptable, acceptable, good, very good) using categorical vehicle features from the UCI Car Evaluation dataset. The dataset contained 1,728 records described by six attributes including buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and safety. The project applied and compared multiple machine learning models and encoding strategies to optimize classification performance.


## USE CASE EXPLANATION:
In automotive marketplaces and recommendation systems, predicting user-centric vehicle ratings based on structured specifications is crucial. This project falls within the domain of consumer analytics and automated decision support systems. The solution supports car manufacturers, retailers, and recommender engines by classifying vehicles into quality categories based on standardized features, aiding purchase recommendations and quality control systems.


## HOW IT IS BUILT AND FULL WORKING:

1. Data Preprocessing:

- Downloaded data from UCI repository.

- Applied two encoding strategies:

- One-Hot Encoding: For tree-based and kernel-based models.

- Ordinal Encoding: For distance-based models like k-NN.

- Handled class imbalance using balanced accuracy as the primary evaluation metric.


2. Models Used:

- Naïve Bayes

- Decision Tree

- Logistic Regression

- k-Nearest Neighbors (k-NN)

-Support Vector Machine (SVM)

3. Model Selection and Evaluation:

- Used nested cross-validation to tune hyperparameters and prevent overfitting.

- Evaluated models using Accuracy, Precision, Recall, F1 Score, and Balanced Accuracy.

- Generated per-class metrics to check if all classes (e.g., “very good”) were predicted equally well.


## OUTPUT AND RESULTS OR BENCHMARKS:

- Best Model: SVM with One-Hot Encoding

- Accuracy, Precision, Recall, F1 Score = 99%

- Consistently strong performance across all classes, minimal misclassification.

- One-hot encoding preserved categorical integrity better than ordinal encoding.

- Other Models:

    1. Decision Tree (98%), Logistic Regression (94%), k-NN (90%), Naïve Bayes (87%)

- Ordinal Encoding worked well for k-NN but reduced performance in other models.


## SKILLS, TOOLS:
Python, scikit-learn, SVM, Decision Trees, k-NN, Logistic Regression, Naïve Bayes, One-Hot Encoding, Ordinal Encoding, Nested Cross-Validation, Multiclass Classification, Model Comparison

## KEYWORDS:
Car classification, consumer analytics, SVM, feature encoding, multiclass prediction, one-hot vs ordinal encoding, class imbalance, nested CV, balanced accuracy, UCI dataset, decision support
