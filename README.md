# Heart Disease Prediction

The objective of this project is to predict the presence of heart disease in patients based on demographic attributes (age, sex), and medical date (e.g. blood pressure, cholesterol, stress test results). 

The primary dataset used for this project is from the following source:   
*fedesoriano. (September 2021). Heart Failure Prediction Dataset. Retrieved [16 Nov 2022] from [kaggle](https://www.kaggle.com/fedesoriano/heart-failure-prediction).*   
It is made available in this repository (heart.csv) under the [Open Database License (ODbL)](https://opendatacommons.org/licenses/odbl/1-0/).

Three prediction models were developed:
- linear support vector machine
- non-linear support vector machine using kernel methods
- feed forward neural network

When using identical training and test sets, linear and non-linear support vector machines achieved the same test accuracy of 88.04%.
Meanwhile, the feed forward neural network achieved slightly lower accurac of 87.5%

Using the linear SVM model we were able to examine the relative magnitude of the coefficients of the various attributes:
- Non-anginal chest pain, atypical angina and an upward slope in the ST segment during exercise were the strongest indicators against the presence of heart disease.
- High fasting blood sugar, being male, and having a flat slope in the ST segment during exercise were the strongest indiactors for the presence of heart disease.
- Least significant features were resting BP and ECG results.