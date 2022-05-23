# Heart Disease Prediction Using Machine Learning

## Problem:
Family is always our first concern, and their health is our priority. Throughout the years, diseases have developed as well as detecting them. One of the most critical diseases is heart disease, and it has been so hard to prevent them from growing to higher stages. 
The human heart is a critical organ in the body, and it delivers blood to every area of our bodies. If it fails to operate properly, the brain and many different organs will stop operating, and thus the human might die after a few minutes. Lifestyle choices, work-related stress, and poor eating habits all lead to the increasing incidence of heart disease. Heart disease has become one of the leading causes of death throughout the world. According to the World Health Organization (WHO), heart disease claims the lives of 17.7 million people each year, representing 31% of all deaths worldwide.

##Solution:
The goal is to predict whether a person has heart disease or not at an early stage.

I have implemented Support Vector Machine (SVM) and MLPClassifer to predict the heart disease.

##Data info:
The dataset contains 303 samples and 14 attributes. The goal of these attributes is to help determine the patient's status using the dataset to see if there are any Disease Symptoms associated with heart disease that leads to heart disease. The following table shows each attribute name and its features. 

| Number | Name                      | Features                                                                                            |
|--------|---------------------------|-----------------------------------------------------------------------------------------------------|
| 1      | Age                       | Number of years the person has   lived                                                              |
| 2      | Sex                       | The gender of the person (Male =1   ,  Female =0)                                                   |
| 3      | Chest Pain (CP)                | The type of chest pain                                                                              |
|        |                       | ·           Value 0: asymptomatic                                                                   |
|        |                           | ·           Value 1: atypical angina                                                                |
|        |                           | ·           Value 2: non-anginal pain                                                               |
|        |                           | ·           Value 3: typical angina                                                                 |
| 4      | Resting Blood Pressure (trestbps)   | The blood pressure of a person (mm Hg)                                                              |
            |
| 5      | Cholesterol (chol)              | The cholesterol measurement of a person  in mg/dl                                                   |                                                                                             |
| 6      | Fasting Blood Sugar (fps)       | fasting blood sugar of a person (> 120   mg/dl,  True=1 ; False=0  )                                |
|        |                     |                                                                                                     |
| 7      | Resting Electrocardiogram (restecg)  | resting electrocardiographic   results                                                              |
|        |                 | ·           Value 0: showing probable or definite left   ventricular hypertrophy by Estes’ criteria |
|        |                           | ·           Value 1: normal                                                                         |
|        |                           | ·           Value 2: having ST-T wave abnormality                                                   |
| 8      | Maximum Heart (thalach)             | The maximum heart rate achieved by a person                                                         |
                                                                                              |
| 9      | Exercise Induced Angina (exang)  | Exercise induced angina (Yes= 1; No =0)                                                             |
                                                                                                   |
| 10     | Stress Test Depression (oldpeak)   | Exercise-induced stress depression compared to   rest                                               |
                                                                                                |
| 11     | Slope for Peak Exercise (slope)  | the slope of the peak exercise   stress segment                                                     |
|        |                    | ·           0: down sloping.                                                                        |
|        |                           | ·           1: flat.                                                                                |
|        |                           | ·           2: upsloping                                                                            |
| 12     | Number of major vessels (ca)  | The number of major vessels ( 0 – 3)                                                                |
                                                                                                  |
| 13     | Thallium Heart Rate (thal)      | thalassemia A blood disorder                                                                        |
|        |                     | ·           Value 1: fixed defect (no blood flow in some part   of the heart)                       |
|        |                           | ·           Value 2: normal blood flow                                                              |
|        |                           | ·           Value 3: reversible defect (a blood flow is   observed but it is not normal)            |
| 14     | Heart disease prediction (target)  | is a person having heart disease  Yes =1    No =0                                                   |
                                                                                                    |
