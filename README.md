This heart disease dataset from www.kaggle.com has 14 attributes.

The dataset gives a number of variables along with a target condition of having or not having heart disease.

The "target" field refers to the presence of heart disease in the patient.

The meaning of the column headers are as follows:

1.age -: The person's age in years

2.sex -:  The person's sex (1 = male, 0 = female)

3.cp -: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)

4.trestbps -: The person's resting blood pressure (mm Hg on admission to the hospital)

5.chol -: The person's cholesterol measurement in mg/dl

6.fbs -: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)

7.restecg -: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)

8.thalach -: The person's maximum heart rate achieved

9.exang -: Exercise induced angina (1 = yes; 0 = no)

10.oldpeak -: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)

11.slope -: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)

12.ca -: The number of major vessels (0-3)

13.thal -: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

14.target -: Heart disease (0 = no, 1 = yes)

•  Exploratory Data Analysis of the Heart Disease dataset was performed to identify the relationship between heart disease and various other features.

•  After EDA data pre-processing was done 10 classification algorithms were used to make the predictions. 

•  10 predictive models were created to predict if a a patient has heart disease or not.

•  Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Extra Trees Classifier, Bagging Classifier, Gradient Boosting Classifier AdaBoost Classifier, Decision Tree, Random Forest, and XGBoost were the algorithms used to create predictive models.

•  XGBoost was selected as the the best classifier by comparing the performance of all the 10 classifiers. The accuracy of XGBoost is 98.54%.
