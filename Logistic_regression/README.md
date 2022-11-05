# Logistic regression project - prediction of heart disease presence

This directory contains a project using logical regression model in order to predict heart disease presence in a patient, based on physical caracteristics (age, gender, cholesterol...).
It is based on a dataset found [here](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

There are 4 datasets - Cleveland, Hungary, Switzerland, and VA Long Beach. All but Cleveland have missing values.
Since the main goal of this project is applying logical regression, we'll only deal with the Cleveland [data](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data).
For a complete example of feature engineering, please refer to the [linear regression](https://github.com/hillelMerran/data-science/tree/main/Linear_regression) project.

## Data Description
The original database contains 76 attributes, but all published experiments refer to using a subset of 14 of them.
Those 14 attributes are based on blood samples and a brief exercise test performed by the patient.
The target field (named 'num') refers to the presence of heart disease. 0 for no heart disease presence, 1 for presence.

### Attributes:
- age: age in years
- sex: sex (1 = male; 0 = female)
- cp: chest pain type
  - Value 1: typical angina
  - Value 2: atypical angina
  - Value 3: non-anginal pain
  - Value 4: asymptomatic
- trestbps: resting blood pressure (in mm Hg on admission to the hospital)
- chol: serum cholestoral in mg/dl
- fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)
- restecg: resting electrocardiographic results
  - Value 0: normal
  - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
  - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- thalach: maximum heart rate achieved
- exang: exercise induced angina (1 = yes; 0 = no)
- oldpeak = ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment
  - Value 1: upsloping
  - Value 2: flat
  - Value 3: downsloping
- ca: number of major vessels (0-3) colored by flourosopy
- thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
- num: diagnosis of heart disease (angiographic disease status)
  - Value 0: < 50% diameter narrowing
  - Value 1: > 50% diameter narrowing
