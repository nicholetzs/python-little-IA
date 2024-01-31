# Python AI Project: Artificial Intelligence and Predictions 🤖
# Case: Customer Credit Score 
You have been hired by a bank to determine the credit score of its customers. 
You need to analyze all bank customers and, based on this analysis, create a model that can read customer information and automatically determine their credit score: Poor, Fair, Good.

# Step-by-Step Explanation: 🔧
# Step 0: Understand the Business Challenge
The initial step is to understand the business problem or challenge that the company is facing. In this case, it involves predicting the credit score of customers.
Step 1: Import the Dataset
The dataset (clientes.csv) is imported using the Pandas library. This dataset contains information about customers.

# Step 2: Prepare the Dataset for AI
The dataset is displayed to visually inspect its structure.
Data cleaning is performed, handling missing values and ensuring the dataset is ready for analysis.

# Step 3: Create an AI Model - Credit Score Prediction
The goal is to create a machine learning model to predict credit scores (Poor, Fair, Good).
The dataset is split into features (x) and the target variable (y), where x contains all features except the credit score, and y is the credit score column.
The dataset is further split into training and testing sets using train_test_split from scikit-learn.

# Step 4: Choose the Best Model
Two models are selected: a Random Forest Classifier and a K-Nearest Neighbors (KNN) Classifier.
Both models are trained on the training set.

# Step 5: Evaluate Model Performance
The accuracy of each model is evaluated on the test set using accuracy_score.
The Random Forest model is found to have an accuracy of 82.8%, while the KNN model has an accuracy of 74.8%.

# Step 6: Make New Predictions
The models are then used to make predictions on a new set of data (novos_clientes.csv), representing new customers.
The professions, credit mix, and payment behavior columns in the new dataset are encoded using LabelEncoder to convert text data into numerical format.
Predictions for credit scores are made using the Random Forest model on the new customer data.
About Random Forest and K-Nearest Neighbors:
Random Forest Classifier:

Ensemble learning method that constructs a multitude of decision trees during training and outputs the mode of the classes.
Well-suited for classification tasks and is known for its robustness and accuracy.
K-Nearest Neighbors (KNN) Classifier:

A type of instance-based learning or lazy learning, where the function is only approximated locally and all computation is deferred until function evaluation.
Predictions are made based on the majority class among the k-nearest neighbors.
This model doesn't include extensive feature engineering or hyperparameter tuning, which are common steps to further improve model performance. The effectiveness of the model depends on various factors, including the quality and quantity of data, model selection, and parameter tuning.

*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧₊˚༺☆༻*ੈ✩‧₊˚*ੈ✩‧
