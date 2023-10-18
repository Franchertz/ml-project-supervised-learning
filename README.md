# MACHINE_LEARNING_PROJECT - SUPERVISED-LEARNING

### DURATION:
Approximately 3 hours and 20 minutes.


### PROJECT DESCRIPTION:

In this projects, you will apply supervised learning techniques to a real-world data set and use data visualization tools to communicate the insights gained from the analysis.

Diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. Symptoms of high blood sugar include frequent urination, increased thirst, and increased hunger. If left untreated, diabetes can cause many complications. Acute complications can include diabetic ketoacidosis, hyperosmolar hyperglycemic state, or death. Serious long-term complications include cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

The dataset for this project is `diabetes.csv` originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

Using supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.The project involves three main parts: exploratory data analysis, preprocessing and feature engineering, and training a machine learning model. 


## PROJECT/GOALS

- 1. Our project has the primary goal of using supervised learning techniques to build a machine learning model that can predict whether a patient has diabetes or not, based on certain diagnostic measurements.

- 2. Communicate these insights to stakeholders using appropriate visualization and metrics. 


## PROCESS

### STEP 1: EXPLORATORY DATA ANALYSIS (EDA)

- 1. Upload dataset: `diabetes.csv`
    
    The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

    - **Pregnancies**: Number of times pregnant
    - **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
    - **BloodPressure**: Diastolic blood pressure (mm Hg)
    - **SkinThickness**: Triceps skin fold thickness (mm)
    - **Insulin**: 2-Hour serum insulin (mu U/ml)
    - **BMI**: Body mass index (weight in kg/(height in m)^2)
    - **DiabetesPedigreeFunction**: Diabetes pedigree function
    - **Age**: Age (years)
    - **Outcome**: Class variable (0 or 1)
    - **Number of Observation Units**: 768
    - **Variable Number**: 9
  
- 2. Clean the dataset.
  
- 3.  Visualize data patterns and correlations

- 4. Prepare for data modelling

- 5. Answer questions: please see Questions_Answers file

### STEP 2: PREPROCESSING & FEATURE ENGINEERING 

- 1. Handle missing values.

- 2. Handle outliers.

- 3. Scaling and normalization

- 4. Feature Engineering

- 5. Handle imbalanced data


### STEP 3: TRAIN ML MODEL

- 1. Train the models: Train the selected models on the training set.

- 2. Model evaluation: Evaluate the trained models on the testing set using appropriate evaluation metrics, such as accuracy, precision, recall, F1-score, and ROC-AUC.

- 3. Improve model performance: perform additional analysis, such as model tuning and cross-validation

- 4. Model comparison: Compare the performance of the selected models and choose the best-performing model based on the evaluation metrics.


### STEP 4: CONCLUSION

Exploratory Data Analysis (EDA) Insights:

- During our exploration of the data, the following were observed:

- 1. Glucose levels exhibit a strong correlation coefficient of approximately 0.47, indicating their significance as a robust indicator of diabetes. In contrast, both BloodPressure and SkinThickness display lower correlation coefficients of around 0.07, suggesting they are weaker indicators of diabetes.

- 2. When the predictor correlations were examined, there are 2 predictor variables that act as a positive correlation to the Outcome dependent variable. These variables are Glucose and BMI, followed by pregnacies. As these increase, Outcome variable increases.

- 3. The age group between 21 and 45 years predominantly experiences diabetes, as revealed by the EDA.

- 4. There is strong interactive effect among the predictor variables.

Machine Model Insights:

- 1. Models chosen were Support Vector Classifier (SVC) and RandomForestClassifier (RFC).

- 2. After training and testing, performed evaluation matrix the RFC model performed better based on accuracy. 

- 3. Further hyperparameter optimization the accuracy of the RFC model stands out at 78%, surpassing that of SVC Model which was at 72%.

- 4. Based on the significant score level Plasma glucose concentration is the most important feature

## RESULTS

RandomForestClassifier (RFC) is the best model for this prediction with 0.78 accuracy.

 