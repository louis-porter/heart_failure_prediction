# Heart Failure Classification

## PROJECT STATUS: COMPLETE


### Introduction
This project uses data from https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data for a classification problem, using a dataset combining features that can machine learning models can use to try and predict heart failure/disease.


### Technologies
- Jupyter Notebook
- Python
    - pandas
    - numpy
    - scikit-learn
    - matplotlib
    - xgboost
    - seaborn


### Data

- Attribute Information
- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' 
 criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]


### Conclusions

The models used in this project all performed well with accuracy scores of over 85% meaning that individuals are correctly classified with heart disease or not the majority of the time.

The Random Forest model performed the best when evaluated against the accuracy score, with the cross validation testing of all 3 models reporting similar figures, suggesting none of the models displayed signs of overfitting.

The most important features for identifying heart disease turned out to be the ST segment during exercise, as well as the oldpeak (ST depression), cholesterol levels, and maximum heart rate. Men are more likely than women to have heart disease, and the older you are, the more likely you are, on average, to have heart disease.