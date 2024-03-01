# UK_Crash_ML_Classifiers
Machine Learning Classification Project using Police UK Crash Data


The objective of this project is to build a machine learning model to predict whether a police officer is likely to attend a road collision accident. The dataset contains locational, temporal, environmental data as well as data about the officers that did or did not attend the scene of the accident.

A "train_data.csv" dataset will be used to train and test machine learning models. Once a model is chosen, it will be used to predict the probability that an officer will attend an accident in the "test_data.csv" dataset.

## Methodology

### 1. Exploratory Data Analysis.
* 1.1 Exploring the data's structure, and features
* 1.2 Outlier Analysis
* 1.3 Handling and aggregating temporal data (preprocessing required for EDA) & Exploring distributions
* 1.4 `LSOA_of_Accident_Location` column data structure
* 1.5 `Local_Authority_(Highway)` column data structure
* 1.6 Correlation Analysis
### 2. Data Preprocessing.
* 2.1 Handling `LSOA_of_Accident_Location` and `Local_Authority_(Highway)`
* 2.2 Converting police attendance to binary
* 2.3 Handling NULL/Missing data
    * `Time` and `LSOA_of_Accident_Location` missing data
### 3. Model Selection & Experimentation.
* 3.1 Creating our feature and target variables and splitting the data into test and train data.
* 3.2 Checking Police Officer Attendance in entire train_data.csv dataset
* 3.3 SGD Classifier
* 3.4 Model 2: HistGradientBoostingClassifier
* 3.5 Model 2: HistGradientBoostingClassifier
* 3.6 Model 4: RandomForestClassifier (RFC)
### 4. Feature Engineering & Model Parameter Tuning
* 4.1 Notes on Model Performance while varying features
* 4.2 SGDClassifier v2
* 4.3 HistGradientBoostingClassifier v2
* 4.4 GradientBoostingClassifier v2
* 4.5 RandomForestClassifier v2
* 4.6 K-Fold Cross Validtion Scores
* 4.7 Class Balancing
* 4.8 Random Search Cross Validation Hyper Parameter Tuning of Random Forest Classifier
### 5. Running Final Model on Test Data
* 5.1 Comparing Target Variable Distribution vs Actual Data 
### 6. Time & Compute Constraints Discussion
### 7. Discussion of Model Deployment
______________________________________________________________________________________________________
